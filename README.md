# fractaldaftar

Market analysis & bug bounty — skills, playbooks, and tools, published as open source.

## What lives here

### 📈 Market analysis

| Repo | What it is |
|---|---|
| [backtesting-trading-strategies](https://github.com/fractaldaftar/backtesting-trading-strategies) | Backtest trading strategies against historical data — 8 strategies, Sharpe/Sortino/drawdown metrics, parameter optimization |
| [hyperliquid](https://github.com/fractaldaftar/hyperliquid) | Trade perps, spot & RWA on Hyperliquid — 32 functions for accounts, PnL, orders, markets & staking |
| [binance](https://github.com/fractaldaftar/binance) | Binance Spot, Futures (USD-S) & Convert via `binance-cli` |
| [polymarket](https://github.com/fractaldaftar/polymarket) | Query Polymarket prediction markets — prices, orderbooks, history (read-only, no auth) |

### 🐛 Bug bounty

| Repo | What it is |
|---|---|
| [bug-chaining](https://github.com/fractaldaftar/bug-chaining) | Low → Critical playbook — 10-question filter, 15 proven chain patterns, escalation ladders |
| [401-403-bypass-techniques](https://github.com/fractaldaftar/401-403-bypass-techniques) | Expert 401/403 bypass playbook — path manipulation, method tampering, header injection |
| [bug-bounty-triage](https://github.com/fractaldaftar/bug-bounty-triage) | Report triage, validation & severity escalation — test it yourself, then ship |
| [cmdi-command-injection](https://github.com/fractaldaftar/cmdi-command-injection) | OS command injection playbook — metacharacters, blind/time-based detection, OOB exfiltration |

## How these are used

Each repo is an **agent skill**: a `SKILL.md` (plus scripts and references) that an AI agent loads when the task matches. Install a skill into your agent's skills directory and invoke it by name.

## Rules of the road

- **Market skills:** backtests are historical simulations, not predictions. Trading involves real risk — never trade money you cannot afford to lose.
- **Security skills:** authorized testing only — bug bounty programs (in-scope targets), pentest engagements, or CTFs. Never test a target you do not own or have explicit written authorization for.

## License

All repos here are MIT licensed, unless a repo states otherwise.
