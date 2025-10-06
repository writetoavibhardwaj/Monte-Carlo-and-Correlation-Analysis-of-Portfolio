# Monte Carlo Bear-Market Stress Test
Python notebook simulating multi-scenario portfolio and SPY performance under 11 macro-regimes  
(normal, tech-collapse, inflation, credit-crunch, etc.)

**Tech stack:** Python 3 · NumPy · Matplotlib · Pandas (optional extension)  

**Core features**
- 10 000 Monte Carlo paths × 5 years = statistical stress testing
- Parametric regime model (`mu`, `vol`) for both portfolio and benchmark
- Relative outperformance summary + visualization
- Reusable for any portfolio weight vector or risk profile

**Next steps**
- Extend to VaR / CVaR calculation
- Build a simple Streamlit dashboard for interactive scenario sliders
- Integrate live SPY data with `yfinance`
