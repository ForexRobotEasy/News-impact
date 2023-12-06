# News Impact Indicator

The News Impact indicator is a custom indicator developed by Forex Robot Easy Team. This indicator summarizes news values and assigns importance levels to help traders make informed trading decisions. Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Product Description

The News Impact indicator is designed to help traders analyze the impact of news events on the market. By summarizing news values and assigning importance levels, this indicator provides valuable insights for making trading decisions.

### Features:

1. Categorization of News Values: The indicator categorizes news values as positive, negative, or neutral, allowing traders to quickly assess the sentiment behind the news.

2. Summarization of News Values: The indicator calculates the summarized news values for a selected period, providing a comprehensive view of the overall impact of news events.

3. Importance Levels: Based on the summarized news values, the indicator assigns importance levels (high, medium, or low) to help traders prioritize their trading decisions.

4. Pie Chart Visualization: The indicator generates a pie chart to visually represent the summarized news values and importance levels. The pie chart is displayed on the News Impact chart, providing a clear and intuitive visualization of the data.

5. Trading Decisions: Traders can use the information from the pie chart to implement their trading logic and make informed trading decisions.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - News Impact Review](https://forexroboteasy.com/forex-robot-review/news-impact-review-forex-software-for-trading-16-currency-pairs/).

## Code Explanation

### Global Variables

- `newsImpactChart`: Chart ID for the News Impact chart.

### Custom Indicator Inputs

- `Period`: Period for summarizing news values.
- `Timeframe`: Timeframe for summarizing news values.

### Custom Indicator Functions

- `CategorizeNews`: A function to categorize news values as positive, negative, or neutral.
- `SummarizeNewsValues`: A function to calculate the summarized news values for a selected period.
- `AssignImportanceLevel`: A function to assign importance levels (high, medium, or low) to the summarized news values.
- `GeneratePieChart`: A function to generate a pie chart to present the summarized news values and importance levels.

### Trading Functions

- `MakeTradingDecisions`: A function to make trading decisions based on the pie chart.

### Initialization

- `OnInit`: Initializes the News Impact chart.

### Deinitialization

- `OnDeinit`: Deinitializes the News Impact chart.

### Start

- `OnStart`: Executes the main logic of the indicator. It summarizes news values for the selected period, assigns importance levels, generates a pie chart, and makes trading decisions based on the pie chart.

Please note that this is a sample code and may need to be customized or integrated with other trading systems to suit specific trading strategies.

For more information about this product and to find the official developer, please refer to MQL5.
