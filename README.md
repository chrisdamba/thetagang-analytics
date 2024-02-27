# Θ ThetaGang Analytics Θ

Thetagang Analytics is a data-driven dashboard for option traders focused on the wheel strategy. Analyse the historical performance of your wheel trades on TQQQ using Interactive Brokers data and optimize your approach with comprehensive backtesting tools.

### Project Features

- **Backtesting:** Simulate the performance of the wheel strategy on TQQQ using historical data from Interactive Brokers.
- **Analysis:** Calculate key metrics like premiums collected, hypothetical P/L, max drawdown, and visualize performance trends.
- **Data Visualization:** Interactive charts to explore historical options data and backtesting results.
- **Technologies:** Python, IBKR API, Remix.js (or Nest.js), [Charting Library], MongoDB (or Time-Series DB), AWS (Lambda, API Gateway, etc.), Terraform.

### Installation

1. **Prerequisites:**
   - Node.js and npm (or yarn)
   - Python 3.x with `ibapi`, `pandas`, etc.
   - Interactive Brokers account with historical data subscriptions.
   - AWS Account (for infrastructure deployment)
2. **Clone Repository:**
   ```bash
   git clone git@github.com:chrisdamba/thetagang-analytics.git
   ```
3. **Set up Environment Variables:**
   - Create `.env` file in the project root to securely store IBKR API credentials and other sensitive information.

### Running the Project

- **Development**
  1. `cd webapp`
  2. `npm install`
  3. `npm run dev`
- **Infrastructure Deployment**
  1.  `cd infrastructure`
  2.  [Outline your Terraform init/plan/apply process]

### API Documentation

- **Endpoints:**
  - `/backtest`: Trigger backtesting simulations.
  - `/metrics`: Retrieve backtesting results.
  - (Add as you develop your API)

### Project Roadmap (optional)

- [List potential future features or enhancements]

### Contributing

[Add contribution guidelines, if applicable]
