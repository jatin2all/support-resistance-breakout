# Support & Resistance Breakout Indicator

This repository contains a TradingView Pine Script indicator that detects breakout signals around recent support and resistance levels.

## Files
- `support_resistance_breakout.pine` — TradingView indicator source

## How it works
- Uses the highest high and lowest low over a configurable lookback period
- Plots support and resistance levels on the chart
- Detects bullish breakouts when price closes above resistance
- Detects bearish breakouts when price closes below support
- Includes alert conditions for both breakout directions

## Install in TradingView
1. Open TradingView
2. Click Pine Editor
3. Paste the contents of `support_resistance_breakout.pine`
4. Save the script
5. Add it to your chart

## Inputs
- Lookback Period: number of candles to calculate support/resistance
- Breakout Buffer: small tolerance to avoid false breakouts
- Show Support/Resistance Levels: toggle lines on or off

## Notes
This is a simple breakout indicator. It works best when combined with trend filters, volume confirmation, or additional signal logic.
