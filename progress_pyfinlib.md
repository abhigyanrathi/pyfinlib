# pyfinlib — Implementation Progress

Tracks module status in the library. Theory coverage is in `topics_covered.md`.

## Legend

| Symbol | Meaning |
|--------|---------|
| ✓ | Complete — tests pass, docstring explains math, Abhi can defend every line |
| ◐ | In progress |
| ✗ | Not started |
| — | Not in scope for pyfinlib |

---

## Repository

| Item | Status |
|------|--------|
| Repo scaffolded | ✓ |
| Editable install (`pip install -e .`) | ✓ |
| pyproject.toml configured | ✓ |
| Linting (ruff) configured | ✓ |
| Type checking (mypy) configured | ✓ |
| CI configured | ✓ |

**Note:** Which topics get implemented in pyfinlib vs. kept to the practice repo is not yet fully decided. Scope gets confirmed as work progresses.

---

## Practice Repo

Separate Git repo for concept practice and Git familiarity. Not pyfinlib. Details TBD.

| Item | Status |
|------|--------|
| Repo created | ✗ |

---

## core/ — Stochastic Processes

| Module | Status | Tests | Chapter |
|--------|:------:|:-----:|---------|
| Wiener process / Brownian motion | ✗ | — | Ch1–2 |
| GBM simulation | ✗ | — | Ch2 |

---

## models/ — Asset Price Models

| Module | Status | Tests | Chapter |
|--------|:------:|:-----:|---------|
| Black-Scholes (BSM) | ✗ | — | Ch3 |
| Local volatility | ✗ | — | Ch4 |
| Merton jump diffusion | ✗ | — | Ch5 |
| Heston stochastic volatility | ✗ | — | Ch8 |
| Bates model | ✗ | — | Ch8 |

---

## pricing/ — Pricing Engines and Payoffs

| Module | Status | Tests | Chapter |
|--------|:------:|:-----:|---------|
| Payoff functions (call, put, digital) | ✗ | — | Ch2–3 |
| P&L analysis | ✗ | — | Ch2–3 |
| BS analytical pricer | ✗ | — | Ch3 |
| Greeks (delta, gamma, vega, theta, rho) | ✗ | — | Ch3 |

---

## numerical/ — Numerical Methods

| Module | Status | Tests | Chapter |
|--------|:------:|:-----:|---------|
| Monte Carlo engine (European, path-dependent) | ✗ | — | Ch2–3 |
| COS method pricer | ✗ | — | Ch6 |
| Crank–Nicolson FDM | ✗ | — | Ch3 |
| Heston COS pricer | ✗ | — | Ch8 |

---

## utils/

To be defined as needed.

---

## Benchmarks (Claude-Written Reference Code)

Four problems completed with Claude assistance before Abhi began independent implementation. These are the numerical answer key — Abhi's re-implementations must match these outputs.

| Problem | Description | Tests |
|---------|-------------|-------|
| Q1 | Call/put payoff functions, vectorised + plotted |  ✗  |
| Q2 | P&L for long/short call and put, breakevens |  ✗  |
| Q3 | GBM simulation, N paths × M steps, path plot |  ✗  |
| Q4 | Monte Carlo European call pricer, convergence to BS |  ✗  |


## Publication Target

Goal: submit pyfinlib to an open-source software journal (e.g. JOSS) post-completion. Acquire real users, collect feedback, demonstrate external adoption to recruiters. Details to be confirmed with mentor.
