# ATR-SB AI-Algo
* ATR-SB AI-Algo is an indicator which works based on calculating the "trend line" from each candle's close price (EMA1) and ATR (average true range). This algorithm starts displaying sell/buy signals based on complex mathematical formulas.

* You can check this indicator out on [this chart](https://www.tradingview.com/chart/dAfm1Hmv/?symbol=BINANCE%3ABTCUSD)

## Indicator Visualization
![Showcase](./imgs/img3.1.png)

## Change log
* 1.0 - Initial push
* 1.1 - Readme edited, Title of the indicator changed
* 1.2 - Added filling, trendline edited, UI and tips added
* 1.3 - Trendline invisible while crossing SB candle, added option to show or hide SB labels
* 1.4 - Stoploss attempt - not working yet
* 1.5 - Stoploss fixed - only one signal per each SB signal
* 1.6 - Stoploss appearance changed
* 1.7 - Stoploss fixed
* 2.0 - Indicator mostly done, first public release
* 2.1 - The whole folder adjusted only for this very indicator
* 2.1.1 - Change of some variable names
* 2.2 - Strategy connected to indicator variables
* 3.0 - Strategy finished, both indicator and strategy newly released as one set
* 3.1 - Removed plots from strategy, fixed stop loss exits
* 3.2 - Better folder organization

## Released Versions
* 2.0 - First public release (indicator only)
* 3.0 - Strategy added for the 2.0 indicator release

## To Do List
- [x] Stop loss plot
- [x] Make strategy for this indicator
- [x] Trend swap does not count as sl
- [ ] Merge it with Consolidation Zones indicator

## Credits
This indicator is inspired by "UT Bot" indicator. My code basically works on it, but I created my version of it. If you want to get some more information about this indicator click [here](https://theforexgeek.com/ut-bot-alerts-indicator/).
