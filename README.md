# pyfinlib

A production-grade Python library implementing quantitative finance models
from Oosterlee & Grzelak's *Mathematical Modelling and Computation in Finance* (Chapters 1–8).

Built as a companion to a structured study of the textbook. Every module
is mathematically derived before implementation and documented to be interview-defensible.

## Scope

- **Ch1**: Stochastic processes, Wiener process, Itô integral — theory only
- **Ch2**: GBM, Itô's lemma, asset price dynamics
- **Ch3**: Black-Scholes PDE, martingale approach, Greeks
- **Ch4**: Local volatility, implied vol surface
- **Ch5**: Jump processes, Lévy processes, Merton model
- **Ch6**: COS method, Fourier pricing
- **Ch7**: Multidimensionality, Girsanov, change of measure
- **Ch8**: Heston stochastic volatility model

## Structure
src/pyfinlib/
core/        # stochastic processes (GBM, Brownian motion)
models/      # asset price models (BSM, Heston, local vol)
pricing/     # pricing engines, Greeks, payoffs
numerical/   # Monte Carlo, FDM, COS method

## Install (development)

```bash
pip install -e ".[dev]"
```

## Run tests

```bash
pytest tests/
```

## Status

Work in progress. Deadline: end of June 2026.

