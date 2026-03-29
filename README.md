# Financial-Econ-Models


### 5-Minute Returns: Jump Detection

- Intraday return construction from 5-min IBM price data (CSV input)
- Diurnal (time-of-day) variation estimation
- Bipower variation (BV) as a jump-robust volatility measure
- Jump detection via a local threshold
- Jump vs. diffusive returns and their densities

### 5-Minute High-Frequency Volatility Analysis

- Diurnal (time-of-day) variation
- Bipower Variation (BV)
- Jump-robust Truncated Variation (TV)
- Theoretical and Bootstrap 95% confidence intervals
- Annualised daily volatility plots

### GMM Estimation for MA(1) and AR(1) Models

- Time series parameter estimation via Generalised Method of Moments
- Matches three moment conditions: mean, second moment, and first-order autocovariance
- MA(1) model: mean, variance, and lag-1 autocovariance moments
- AR(1) model: unconditional moments derived from stationarity conditions
- Stationarity constraints enforced (|θ| < 1, |φ| < 1) via trust-region optimisation
- Identity weighting matrix (first-step GMM)
- Side-by-side summary of both sets of estimates