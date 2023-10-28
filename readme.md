# VIX Rank Percentile Indicator for Think or Swim

## Description

The VIX Rank Percentile Indicator is a custom ThinkScript indicator for the Think or Swim (ToS) trading platform. It calculates the percentile rank of the current Volatility Index (VIX) value in relation to its past values over a specified lookback period. The percentile rank is plotted on the chart, and it provides insights into market volatility, helping traders to make more informed decisions.

### Why Is It a Good Trading Indicator?

The VIX is often referred to as the "fear gauge" of the market. When the VIX is high, it generally means that there's a lot of uncertainty, and prices may swing widely. Conversely, a low VIX typically indicates a more stable market. The VIX Rank Percentile helps to normalize these values by comparing the current VIX to its past levels. This can give traders a better idea of whether the current market volatility is unusual or typical, enabling more strategic trading decisions.

## Input Settings

- `lookBackDays`: The number of past trading days to consider for calculating the percentile rank. Default is 100 days.
- `lowerPercentileThreshold`: The lower percentile threshold for coloring the indicator. Default is 40.
- `upperPercentileThreshold`: The upper percentile threshold for coloring the indicator. Default is 90.

### Lookback Periods

- **Shorter Period**: A shorter lookback period (e.g., 20-30 days) will make the indicator more sensitive to recent changes in volatility. This is useful for short-term trading strategies.
- **Medium Period**: A medium lookback period (e.g., 50-70 days) provides a balanced view and is useful for swing traders.
- **Longer Period**: A longer lookback period (e.g., 100 days or more) will smooth out the indicator and is more suited for long-term investment strategies.

## Installation Instructions

1. Open Think or Swim platform.
2. Go to `Charts` tab.
3. Click on the `Studies` button (it looks like a flask).
4. Click on `Edit Studies...`.
5. In the `Studies` pane, click on `Create` to create a new study.
6. Name your study and paste the ThinkScript code into the editor.
7. Click on `OK` to save the study.
8. The VIX Rank Percentile Indicator should now be applied to your chart. You can adjust the settings by clicking on the gear icon next to the study name in the `Studies` pane.

---

Feel free to adjust the settings and the lookback period to better suit your trading strategy.
![Input Settings](https://github.com/AndrewJesse/VIXRankPercentile/assets/53543737/545a62c7-01b4-47d4-84a6-865a08861508)

