**Please see the PDF file for the theoretical framework and detailed methodology underlying the trend-following strategy.**

*Abstract*

I replicate the SG Trend Index using the bottom-up and top-down
decomposition of Jungle Rock (2024), with a different estimator for
each component. The bottom-up component clusters 560 risk-parity trend
strategies on their correlation structure alone, then fits a
non-negative Lasso on the cluster medoids. The top-down component is a
rolling Lasso on ten futures. Out of sample and net of transaction
costs, their equal-weight combination earns 6.17% a year at 12.06%
volatility, with a Sharpe ratio of 0.51 against 0.18 for the index and a
correlation to the index of 0.78.

Robustness checks use the Probabilistic Sharpe Ratio (PSR) and repeat
the backtest from every possible entry week in the out-of-sample period.
The replication's Sharpe ratio exceeds the benchmark's at 98.54% of
entry weeks, but a PSR of 0.89 falls short of the conventional 0.95
level, so the evidence of excess return is suggestive rather than
conclusive.
