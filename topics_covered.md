# Topics Covered — Oosterlee & Grzelak (Ch1–8)

Tracks theory understanding only. Implementation status is in `progress_pyfinlib.md`.

## Legend

| Symbol | Meaning |
|--------|---------|
| ✓ | Can derive from scratch, solo, without notes |
| ◐ | Exposed; cannot fully reproduce solo |
| ✗ | Not yet covered |

---

## Chapter 1 — Basics about Stochastic Processes
*Theory only. No implementation expected.*

| Section | Theory |
|---------|:------:|
| **1.1 Stochastic variables** | ✗ |
| 1.1.1 Density function, expectation, variance | ✗ |
| 1.1.2 Characteristic function | ✗ |
| 1.1.3 Cumulants and moments | ✗ |
| **1.2 Stochastic processes, martingale property** | ✗ |
| 1.2.1 Wiener process | ✗ |
| 1.2.2 Martingales | ✗ |
| 1.2.3 Iterated expectations (Tower property) | ✗ |
| **1.3 Stochastic integration, Itô integral** | ✗ |
| 1.3.1 Elementary processes | ✗ |
| 1.3.2 Itô isometry | ✗ |
| 1.3.3 Martingale representation theorem | ✗ |

---

## Chapter 2 — Introduction to Financial Asset Dynamics

| Section | Theory |
|---------|:------:|
| **2.1 Geometric Brownian motion asset price process** | ✗ |
| 2.1.1 Itô process | ✗ |
| 2.1.2 Itô's lemma | ✗ |
| 2.1.3 Distributions of S(t) and log S(t) | ✗ |
| **2.2 First generalizations** | ✗ |
| 2.2.1 Proportional dividend model | ✗ |
| 2.2.2 Volatility variation | ✗ |
| 2.2.3 Time-dependent volatility | ✗ |
| **2.3 Martingales and asset prices** | ✗ |
| 2.3.1 P-measure prices | ✗ |
| 2.3.2 Q-measure prices | ✗ |
| 2.3.3 Parameter estimation under real-world measure P | ✗ |

---

## Chapter 3 — The Black-Scholes Option Pricing Equation

| Section | Theory |
|---------|:------:|
| **3.1 Option contract definitions** | ✗ |
| 3.1.1 Option basics | ✗ |
| 3.1.2 Derivation of the partial differential equation | ✗ |
| 3.1.3 Martingale approach and option pricing | ✗ |
| **3.2 The Feynman-Kac theorem and the Black-Scholes model** | ✗ |
| 3.2.1 Closed-form option prices | ✗ |
| 3.2.2 Green's functions and characteristic functions | ✗ |
| 3.2.3 Volatility variations | ✗ |
| **3.3 Delta hedging under the Black-Scholes model** | ✗ |

---

## Chapter 4 — Local Volatility Models

| Section | Theory |
|---------|:------:|
| **4.1 Black-Scholes implied volatility** | ✗ |
| 4.1.1 The concept of implied volatility | ✗ |
| 4.1.2 Implied volatility; implications | ✗ |
| 4.1.3 Discussion on alternative asset price models | ✗ |
| **4.2 Option prices and densities** | ✗ |
| 4.2.1 Market implied volatility smile and the payoff | ✗ |
| 4.2.2 Variance swaps | ✗ |
| **4.3 Non-parametric local volatility models** | ✗ |
| 4.3.1 Implied volatility representation of local volatility | ✗ |
| 4.3.2 Arbitrage-free conditions for option prices | ✗ |
| 4.3.3 Advanced implied volatility interpolation | ✗ |
| 4.3.4 Simulation of local volatility model | ✗ |

---

## Chapter 5 — Jump Processes

| Section | Theory |
|---------|:------:|
| **5.1 Jump diffusion processes** | ✗ |
| 5.1.1 Itô's lemma and jumps | ✗ |
| 5.1.2 PIDE derivation for jump diffusion process | ✗ |
| 5.1.3 Special cases for the jump distribution | ✗ |
| **5.2 Feynman-Kac theorem for jump diffusion process** | ✗ |
| 5.2.1 Analytic option prices | ✗ |
| 5.2.2 Characteristic function for Merton's model | ✗ |
| 5.2.3 Dynamic hedging of jumps with the Black-Scholes model | ✗ |
| **5.3 Exponential Lévy processes** | ✗ |
| 5.3.1 Finite activity exponential Lévy processes | ✗ |
| 5.3.2 PIDE and the Lévy triplet | ✗ |
| 5.3.3 Equivalent martingale measure | ✗ |
| **5.4 Infinite activity exponential Lévy processes** | ✗ |
| 5.4.1 Variance Gamma process | ✗ |
| 5.4.2 CGMY process | ✗ |
| 5.4.3 Normal inverse Gaussian process | ✗ |
| **5.5 Discussion on jumps in asset dynamics** | ✗ |

---

## Chapter 6 — The COS Method for European Option Valuation

| Section | Theory |
|---------|:------:|
| **6.1 Introduction into numerical option valuation** | ✗ |
| 6.1.1 Integrals and Fourier cosine series | ✗ |
| 6.1.2 Density approximation via Fourier cosine expansion | ✗ |
| **6.2 Pricing European options by the COS method** | ✗ |
| 6.2.1 Payoff coefficients | ✗ |
| 6.2.2 The option Greeks | ✗ |
| 6.2.3 Error analysis COS method | ✗ |
| 6.2.4 Choice of integration range | ✗ |
| **6.3 Numerical COS method results** | ✗ |
| 6.3.1 Geometric Brownian Motion | ✗ |
| 6.3.2 CGMY and VG processes | ✗ |
| 6.3.3 Discussion about option pricing | ✗ |

---

## Chapter 7 — Multidimensionality, Change of Measure, Affine Processes

| Section | Theory |
|---------|:------:|
| **7.1 Preliminaries for multi-D SDE systems** | ✗ |
| 7.1.1 The Cholesky decomposition | ✗ |
| 7.1.2 Multi-D asset price processes | ✗ |
| 7.1.3 Itô's lemma for vector processes | ✗ |
| 7.1.4 Multi-dimensional Feynman-Kac theorem | ✗ |
| **7.2 Changing measures and the Girsanov theorem** | ✗ |
| 7.2.1 The Radon-Nikodym derivative | ✗ |
| 7.2.2 Change of numéraire examples | ✗ |
| 7.2.3 From P to Q in the Black-Scholes model | ✗ |
| **7.3 Affine processes** | ✗ |
| 7.3.1 Affine diffusion processes | ✗ |
| 7.3.2 Affine jump diffusion processes | ✗ |
| 7.3.3 Affine jump diffusion process and PIDE | ✗ |

---

## Chapter 8 — Stochastic Volatility Models

| Section | Theory |
|---------|:------:|
| **8.1 Introduction into stochastic volatility models** | ✗ |
| 8.1.1 The Schöbel-Zhu stochastic volatility model | ✗ |
| 8.1.2 The CIR process for the variance | ✗ |
| **8.2 The Heston stochastic volatility model** | ✗ |
| 8.2.1 The Heston option pricing partial differential equation | ✗ |
| 8.2.2 Parameter study for implied volatility skew and smile | ✗ |
| 8.2.3 Heston model calibration | ✗ |
| **8.3 The Heston SV discounted characteristic function** | ✗ |
| 8.3.1 Stochastic volatility as an affine diffusion process | ✗ |
| 8.3.2 Derivation of Heston SV characteristic function | ✗ |
| **8.4 Numerical solution of Heston PDE** | ✗ |
| 8.4.1 The COS method for the Heston model | ✗ |
| 8.4.2 The Heston model with piecewise constant parameters | ✗ |
| 8.4.3 The Bates model | ✗ |
