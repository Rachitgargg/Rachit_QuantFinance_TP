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

RELIANCE | 2 | 0% | Would not trade based on this test alone

Based on this test, I would not feel comfortable trading this strategy with my own money yet. The strategy made only two completed trades during the 12-month period, and both ended in losses. The first trade lost around 0.50%, while the second lost about 5.39%, giving the strategy a 0% win rate.
At the same time, I think it is too early to say that the strategy completely does not work. Two trades is a very small sample size, so the results may not represent how the strategy would perform over a longer period. I would want to test it on more stocks and over a longer time before making a final decision.

One weakness I noticed is that the EMA crossover is a lagging signal. This means the strategy can enter after a price move has already started and may also exit late, giving back some gains. It may struggle when the market is moving/changing direction quickly.
Overall, the results are not very encouraging, but I would need more testing before deciding whether the strategy has a real advantage.

#BONUS

I designed a simple trend-following strategy using the 20-day EMA, 50-day EMA and RSI. The 20/50 EMA relationship is used to identify the broader direction of the trend, while the RSI is used as a momentum filter. I use the price crossing above the 20 EMA as the actual entry trigger rather than entering solely because the two EMAs are bullish. This is intended to avoid entering too early after a trend change. For risk management, I use a 5% stop-loss and exit when the closing price falls below the 20 EMA. The strategy is completely rule-based so that the same conditions can be applied consistently across different stocks without subjective judgement.

The strategy behaved differently across the two stocks. On TCS, the strategy generated 4 trades with 1 winner and 3 losers, giving a 25% win rate. The largest winning trade returned 2.93%, while the largest losing trade lost 2.22%. On HDFC Bank, the strategy generated 5 trades and all 5 were losing trades, resulting in a 0% win rate. The largest loss was 6.30%, which was significantly larger than any loss recorded on TCS.
This suggests that the strategy was not very robust across different stocks. TCS produced at least one profitable trend, while HDFC Bank produced several short-lived signals that resulted in small losses and one much larger loss. One possible reason is that EMA-based strategies work better when a stock is moving in a sustained direction, but can generate repeated false signals when the price is moving sideways or changing direction frequently. The difference between the two stocks shows that a strategy should not be judged from its performance on just one instrument.

#Verdict

TCS | 4 Trades | 25% Win Rate | Weak, but showed some potential
I would not trade this strategy with my own money in its current form. The results were weak, with only one winning trade out of four. However, the strategy did manage to capture one profitable move, returning 2.93%, and the losses were relatively contained compared with the winning trade. The main weakness is that the strategy can enter trades during short-term movements that do not develop into sustained trends.
The comparison with HDFC Bank makes me less confident in the strategy. HDFC Bank produced five trades with a 0% win rate, including a 6.30% loss. This suggests that the strategy is highly dependent on the behaviour of the individual stock and may work better during strong trending periods than during sideways or volatile markets. Before risking real money, I would test the strategy over a much longer period and across more stocks, and I would consider adding a filter to avoid taking signals when the market is moving sideways.
