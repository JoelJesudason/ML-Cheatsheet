# Machine Learning Cheatsheet
Machine learning cheatsheet

## Hodrick-Prescott Filtering

### Decomposing into trend and noise

'''
import statsmodels.api as sm
ts_noise, ts_trend = sm.tsa.filters.hpfilter(df['close'])
'''


### Autocorrelation, Partial-Autocorrelation
