# Harrison Rush

Machine learning engineer working on reinforcement learning, graph neural
networks, forecasting systems, and the infrastructure needed to evaluate models
honestly.

I like projects where the model is only one part of the system: data quality,
simulation, replay, calibration, deployment, and postmortems all matter.

## What I Work On

- Reinforcement learning for constrained decision-making with graph neural
  networks and PPO.
- ML experimentation systems: reproducible runs, sweeps, MLflow-style tracking,
  checkpointing, evaluation harnesses, and replay tooling.
- Forecasting systems that connect live data, model outputs, decisions, and
  resolved outcomes.
- Small, practical tools in Rust and Python.

## Selected Work

### TinyChat

[`tinychat`](https://github.com/hrush98/tinychat) is a lightweight Rust terminal
chat router and tuning workbench for local and self-hosted language models. It
targets OpenAI-compatible chat endpoints, streaming output, profile-based
routing, and debugging visibility for model behavior.

### RoboWeather

RoboWeather is a proprietary weather-forecasting and market-research system. The
public description is intentionally high-level: it connects live observations,
forecast guidance, model calibration, market data, replay ledgers, and outcome
resolution for same-day temperature forecasting research.

I do not present it as a finished profitable trading system. The strongest part
of the work is the research infrastructure: snapshot collection, fair-value
modeling, policy replay, failure analysis, and calibration from resolved
outcomes.

### League of Legends Esports Bot

Planned public artifact. The best open-source version would be a sanitized repo
focused on data ingestion, schedule/results parsing, team and player features,
matchup modeling, backtesting, and a Discord or CLI bot interface.

Keep out private credentials, betting/execution logic, unpublished datasets, and
anything copied from a private production codebase. A strong public version can
still show the important engineering: schemas, feature builders, model
evaluation, simulations, tests, and a clear bot UX.

## Good Repos To Pin

- `tinychat` once the README has a short demo GIF or terminal transcript.
- A new `lol-esports-bot` repo with clean sample data, tests, and a reproducible
  backtest.
- This resume workspace if it is moved under `hrush98` and includes generated
  PDFs through releases rather than committed build artifacts.

## Contact

- GitHub: [`hrush98`](https://github.com/hrush98)
- Email: `hrush9212@gmail.com`
