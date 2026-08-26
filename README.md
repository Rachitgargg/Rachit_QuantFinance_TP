# FINOVA Quant & Trading Committee — 20/50 EMA Crossover Backtest
Instrument- Reliance Industries Ltd (NSE: RELIANCE)

Period-26 August 2025 – 26 August 2026

Strategy used- Buy when the 20-day EMA crosses above the 50-day EMA. Exit when the 20-day EMA crosses below the 50-day EMA.

Values used - I used the closing price of the crossover-confirmation day as the entry/exit price and applied this convention consistently to all trades.

| Metric         | Result |
| -------------- | -----: |
| Total Trades   |      2 |
| Winners        |      0 |
| Win Rate       |     0% |
| Largest Winner |    N/A |
| Largest Loser  | −5.39% |

RELIANCE | 2 Trades | 0% Win Rate
Based on this test, I would not feel comfortable trading this strategy with my own money yet. The strategy made only two completed trades during the 12-month period, and both ended in losses. The first trade lost around 0.50%, while the second lost about 5.39%, giving the strategy a 0% win rate.
At the same time, I think it is too early to say that the strategy completely does not work. Two trades is a very small sample size, so the results may not represent how the strategy would perform over a longer period. I would want to test it on more stocks and over a longer time before making a final decision.

One weakness I noticed is that the EMA crossover is a lagging signal. This means the strategy can enter after a price move has already started and may also exit late, giving back some gains. It may struggle when the market is moving/changing direction quickly.
Overall, the results are not very encouraging, but I would need more testing before deciding whether the strategy has a real advantage.
