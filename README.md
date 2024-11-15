# QuantConnect Trading Strategies

This repository provides algorithmic trading strategies tailored for use on the QuantConnect platform. Each strategy is designed to leverage QuantConnect's powerful data access, backtesting, and live trading capabilities.

## Repository Overview

- **Trading Strategies**: Includes a range of strategies such as options straddles, triangular arbitrage, and crypto trend following, designed for various markets and trading styles.
- **Modular Design**: Each strategy is organized in a modular format, making it easy to customize or extend within QuantConnect.
- **Backtesting Ready**: All strategies can be backtested directly in QuantConnect to evaluate performance and refine parameters before live deployment.

## How to Use

1. **Clone or Download**: Clone this repository or download individual strategy files as needed.
   
2. **Upload to QuantConnect**:
   - Go to the [QuantConnect](https://www.quantconnect.com/) platform.
   - Create a new project or open an existing one.
   - Upload the strategy files into your QuantConnect project.

3. **Backtest the Strategy**:
   - In QuantConnect, select your desired strategy and configure the backtest settings.
   - Run the backtest to see performance results and make adjustments as necessary.

4. **Deploy Live** (Optional):
   - Once you’re satisfied with the backtesting results, you can set up the strategy for live trading through QuantConnect’s brokerage integrations.

## Strategies Included

- **Options Straddles**: Implements a volatility-based options straddle strategy.
- **Triangular Arbitrage**: Exploits price discrepancies between pairs in a single exchange.
- **Crypto Trend Following**: A crypto strategy using popular technical indicators.

## Contribution

If you would like to add new strategies or improve existing ones, feel free to fork this repository and submit a pull request.
