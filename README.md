# StockTrading

This is a custom environment for the DeepAI Gym library that simulates stock trading using historical stock price data. It allows an agent to learn how to make profitable trades based on technical indicators and market conditions. The environment supports both single-stock and multi-stock trading and provides various configuration options for hyperparameter tuning.

# Ichimoku Trading Strategy

This repository contains the implementation of the Ichimoku trading strategy using Python and Pandas library. The Ichimoku Cloud is a technical analysis tool that utilizes multiple lines on a price chart to better identify potential buy and sell signals. In this project, we calculate the key components of the Ichimoku Cloud, including the conversion line, baseline, leading span A, leading span B, and lagging span. We also include additional technical indicators such as the stochastic RSI.

## Usage

To use this environment, you can create an instance of the `StockTradingEnv` class and call its `reset()` method to initialize the state. The state contains the current asset value, stock prices, technical indicators, and other relevant information. You can then call the `step()` method to take an action (i.e., buy or sell a certain number of shares) and receive a reward (i.e., the change in asset value), as well as other information such as the total cost, total trades, and total rewards earned so far. The `render()` method can be used to visualize the state, although it is currently only implemented for human-friendly output.

## Contributing

Contributions are welcome! If you have any improvements or suggestions for this project, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
