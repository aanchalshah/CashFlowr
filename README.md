# CashFlowr - Personal Finance Manager & Expense Tracker

A comprehensive web application for managing personal finances, tracking expenses, setting budgets, and achieving financial goals. Built with modern React and designed for the Indian market with Rupee (₹) currency support.

## Features

### 📊 Dashboard
- Overview of total income, expenses, and net worth
- Interactive pie chart showing expense distribution by category
- Monthly income vs expenses bar chart
- Account balance summary
- Financial goals progress preview

### 💰 Transaction Management
- Add, edit, and delete income and expense transactions
- Custom category support with the ability to add new categories
- Transaction filtering by type and category
- Date-based transaction organization
- Detailed transaction history with search and filter options

### 🎯 Budget Tracking
- Create and manage budgets for different categories
- Visual progress bars showing budget utilization
- Smart alerts when approaching or exceeding budget limits
- Monthly and yearly budget periods
- Budget vs actual spending comparison

### 🏆 Financial Goals
- Set and track financial goals with target amounts
- Visual progress tracking with completion percentages
- Deadline management with countdown timers
- Goal contribution tracking
- Achievement notifications

### 🔔 Smart Notifications
- Budget alerts when nearing or exceeding limits
- Goal milestone notifications
- Deadline reminders for financial goals
- Automated notification generation based on financial activities

### 📱 Responsive Design
- Mobile-first design approach
- Optimized for tablets and desktop
- Touch-friendly interface
- Consistent experience across all devices

## Technology Stack

- **Frontend**: React 18 with TypeScript
- **State Management**: React Context API with useReducer
- **Styling**: Tailwind CSS
- **Charts**: Recharts for data visualization
- **Icons**: Lucide React
- **Date Handling**: date-fns
- **Build Tool**: Vite

## Getting Started

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd personal-finance-manager
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

## Project Structure

```
src/
├── components/          # React components
│   ├── Dashboard.tsx    # Main dashboard with charts
│   ├── TransactionForm.tsx  # Add/edit transaction form
│   ├── TransactionList.tsx  # Transaction history
│   ├── BudgetManager.tsx    # Budget management
│   ├── GoalManager.tsx      # Financial goals
│   ├── NotificationPanel.tsx # Notifications
│   └── Navbar.tsx           # Navigation component
├── context/             # State management
│   └── FinanceContext.tsx   # Global state context
├── types/               # TypeScript type definitions
│   └── index.ts
├── App.tsx              # Main application component
├── main.tsx             # Application entry point
└── index.css            # Global styles
```

## Features in Detail

### Dashboard Analytics
- **Financial Overview**: Real-time calculation of total income, expenses, and net worth
- **Expense Breakdown**: Interactive pie chart showing spending by category
- **Trend Analysis**: Monthly comparison of income vs expenses
- **Account Summary**: Overview of all linked accounts and balances

### Transaction Management
- **Quick Entry**: Fast transaction entry with intelligent categorization
- **Bulk Operations**: Edit or delete multiple transactions
- **Smart Categorization**: Auto-suggestions based on transaction history
- **Advanced Filtering**: Filter by date range, amount, category, or type

### Budget Intelligence
- **Predictive Alerts**: Early warnings when spending patterns indicate budget overruns
- **Category Insights**: Deep dive into spending patterns by category
- **Historical Comparison**: Compare current spending with previous periods
- **Budget Optimization**: Suggestions for better budget allocation

### Goal Achievement
- **Visual Progress**: Beautiful progress indicators with milestone celebrations
- **Smart Savings**: Automatic calculations for required monthly savings
- **Deadline Management**: Intelligent deadline tracking with priority alerts
- **Achievement Rewards**: Celebration animations for completed goals

## Data Persistence

The application uses localStorage to persist data between sessions. All financial data is stored locally on your device, ensuring privacy and offline functionality.

## Privacy & Security

- All data is stored locally in your browser
- No data is transmitted to external servers
- Secure local storage implementation
- No account registration required

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For support, please open an issue in the GitHub repository or contact the development team.

## Roadmap

- [ ] Data export/import functionality
- [ ] Multi-currency support
- [ ] Bank account integration
- [ ] Advanced reporting features
- [ ] Mobile app version
- [ ] Cloud sync capabilities
- [ ] Investment tracking
- [ ] Bill reminders
- [ ] Receipt scanning
- [ ] Financial advice integration