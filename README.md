# Liquidity + Imbalance [LW]

A TradingView Pine Script v5 overlay indicator for liquidity sweep signals and fair value gaps (FVGs).

## Features

- Detects liquidity sweeps around recent pivot highs and lows.
- Marks sweeps with chart labels, dashed level lines, and directional triangles.
- Finds bullish and bearish three-candle fair value gaps.
- Filters FVGs by minimum size and middle-candle impulse strength.
- Draws FVG boxes with optional midlines and hides gaps after mitigation.
- Shows a compact signal status table on the chart.

## Use

1. Open [TradingView](https://www.tradingview.com/).
2. Open the Pine Editor and paste the contents of [liquidity-imbalance.pine](./liquidity-imbalance.pine).
3. Select **Add to chart**.

## Inputs

The inputs control swing length, sweep and label visibility, FVG and midline visibility, minimum FVG size, and whether mitigated gaps are hidden.

## Notes

The script is provided as-is. Signals are based on the rules in the source and should be evaluated on your chart and timeframe; this repository does not make a performance or accuracy guarantee.

## License

Licensed under the MIT License; see [LICENSE](./LICENSE).
