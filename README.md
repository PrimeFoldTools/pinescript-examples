# PineScript v5 Examples

Educational PineScript v5 examples for TradingView. Clean, well-commented scripts covering strategies, indicators, and risk management patterns.

Built for traders who value **process over prediction** — rules-based systems, mechanical decisions, and disciplined risk management.

## Examples

| File | Description |
|------|-------------|
| [EMA Crossover Strategy](examples/ema-crossover-strategy.pine) | Classic EMA crossover with stop loss, take profit, and position sizing |
| [ATR Trailing Stop](examples/atr-trailing-stop.pine) | Dynamic trailing stop based on Average True Range |
| [Session Volume Profile](examples/session-volume-profile.pine) | Volume broken down by trading session (Asian / London / New York) |
| [Risk/Reward Overlay](examples/risk-reward-overlay.pine) | Visualize risk/reward zones on chart before entering a trade |
| [Multi-Timeframe EMA](examples/multi-timeframe-ema.pine) | Higher timeframe EMA plotted on lower timeframe chart using `request.security()` |
| [Trade Session Filter](examples/trade-session-filter.pine) | Filter strategy entries to specific trading sessions only |

## Usage

1. Open [TradingView](https://www.tradingview.com/) and go to the Pine Script Editor
2. Copy any `.pine` file contents into the editor
3. Click **Add to Chart**

Each script is self-contained and ready to use. Read the comments in each file for explanations of the logic.

## Philosophy

These examples reflect a constraint-based approach to trading:

- **Rules over discretion** — Define your system, then follow it
- **Risk management first** — Every strategy includes stops and position sizing
- **Mechanical decisions** — Remove emotion from the process

No proprietary logic here — just clean patterns you can learn from and build on.

## License

MIT License. See [LICENSE](LICENSE) for details.

---

Built by [PrimeFold.Tools](https://primefold.tools)
