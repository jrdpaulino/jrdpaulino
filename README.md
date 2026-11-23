# Hi, I'm Julian Paulino

I build data and machine-learning systems and I like testing ideas properly: a held-out period, a stated pass mark,
and an honest write-up when the idea fails.

## Projects

**[Market Signal Conductor](https://github.com/jrdpaulino/market-signal-conductor)**: a web service that combines
SEC filings, prediction-market odds, macro data and news in a layered Markov model of the market cycle, then scores
every forecast against what the market did next. Python, SQLite, Fly.io, 61 tests, no third-party dependencies.

**[EDGAR Insider Copy-Trader](https://github.com/jrdpaulino/edgar-insider-copytrader)**: an SEC Form 4 insider-buying
agent with a risk gate, plus backtests with a holdout period. No edge found, and the write-up shows the numbers.

**[Machine Learning Models](https://github.com/jrdpaulino/Machine-Learning-Models)**: an MLP against LeNet-5 on MNIST,
Fashion-MNIST and CIFAR-10 in PyTorch, with a results table and one-click Colab notebooks.

**[Congress Copy-Trader](https://github.com/jrdpaulino/congress-copytrader)**: the first version of the trading
agent, kept to show how the work progressed.

## What I use

Python, PyTorch, SQL and SQLite, statistics and backtesting, Docker, Fly.io, GitHub Actions, C.

## How the work fits together

The trading repos are a sequence: a Congress disclosure agent, then an insider-filings agent with backtests, then a
model whose own forecast record decides whether it is ever allowed to trade. The write-up of what each step taught is
in [`docs/PROGRESS.md`](https://github.com/jrdpaulino/edgar-insider-copytrader/blob/main/docs/PROGRESS.md).
