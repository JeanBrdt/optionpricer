# optionpricer

Option pricing library in Python, built from first principles:
closed-form, Monte Carlo and finite-difference methods, with convergence studies.

## Roadmap

- [ ] Black-Scholes closed form (price, Greeks, put-call parity tests)
- [ ] Monte Carlo pricer + 1/√N convergence study
- [ ] Variance reduction (antithetic variates, control variates)
- [ ] Finite differences: explicit, implicit, Crank-Nicolson + order of convergence
- [ ] Numerical vs analytical Greeks
- [ ] American options (PDE with early-exercise constraint, Longstaff-Schwartz)
- [ ] Implied volatility
- [ ] Extensions: Heston / barrier options

## Installation

    pip install -e ".[dev]"
    pytest

## Author

Jean Brandicourt — IMT Atlantique
