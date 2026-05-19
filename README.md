# CVA Pricer — Interest Rate Swap

This project computes the Credit Valuation Adjustment (CVA)
for an interest rate swap, implemented in Python using the
Black-76 swaption replication approach.

## What this covers

**Notebook 1 — Derivatives Pricing (CCR_1.ipynb)**
- Interest rate swap pricing (par rate, level, PV01)
- Swaption pricing under Black-76 (payer & receiver, Greeks)
- Cap and floor valuation
- Delta hedging strategy with stress testing (±50bps)

**Notebook 2 — CVA Calculation (CCR_2.ipynb)**
- Expected Exposure (EE) profile using swaption replication
- CVA = Σ LGD × EE_i × PD_i across all payment intervals
- CVA sensitivities: PV01, Vega, CS01
- Stress testing across ±200bps parallel rate shifts

## Tools
Python — NumPy, SciPy, Pandas, Matplotlib
