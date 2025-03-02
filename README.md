# Consecutive-Z 1.0
# Previous approach
namely consecutive x
- I'm looking to optimize the following variables to improve signal generation: the multiplier applied to the Average True Range for both stop-loss and take-profit calculations, and the required number of consecutive bullish or bearish candles needed to trigger a signal.
- My ideal workflow is streamlined and efficient. I only need to generate trading signals—specifically entry prices, take-profit, and stop-loss levels—manually, based on a quick morning review of this indicator. I want to minimize the time spent on this task. Essentially, I'd like to glance at the chart with the indicator, make a rapid decision whether to create a signal, and then be finished for the day.

# New approach
- address the delay of the execution from the signal, this should be in the backtest
- only execute in work hours only
- work in both trend direction
- using lucit backtesting with compatible python version
- great plotting view