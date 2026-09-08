# BS-GCFP v1

For each covered economy, the latest non-null World Bank observation for portfolio investment, net (BoP, current US$) is retained with its own reference year.

The UI normalizes each observation against the largest absolute observation in the current covered cross-section:

`score = 50 + 45 × clamp(net portfolio investment / max absolute observation, -1, 1)`

A score above 50 indicates positive net portfolio-investment pressure relative to the cross-section; below 50 indicates negative pressure. This is a BondStats analytical visualization, not a forecast, official indicator, investment recommendation or real-time transfer measure.
