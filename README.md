# Machine Learning Cheatsheet
Time Series, Classification, and Deep Learning

## Hodrick-Prescott Filtering

Useful for decomposing time series. 

4 elements of time series decomposition:
 - Level (average of series)
 - Trend (direction)
 - Periodicity (cyclicality)
 - Residual (how much randomness)

### Decomposing into trend and noise

```
import statsmodels.api as sm
ts_noise, ts_trend = sm.tsa.filters.hpfilter(df['close'])
```


## Autocorrelation, Partial-Autocorrelation

