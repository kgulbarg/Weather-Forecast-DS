### Obsrvations
1. Some country names are represented with localized country names and non-English character representations
2. The circular histogram revealed that wind directions are not uniformly distributed across all angles. Instead, several directional concentrations were observed, suggesting prevailing wind patterns and regional climatic biases within the dataset.

3. Based on Pearson correlation, air pollution features are all positively correlated except Ozoen and PM 10. This is consistent with the pollutants released sue to urban human pollution like vehicular exhausts etc. 

4. The `temperature_celsius` vs `feels_like_celsius` scatter plot shows a strong positive linear relationship between actual and perceived temperature. Around the moderate temperature range (~16°C to 22°C), the feels-like temperature closely matches the measured temperature, lying near the y = x reference line.
5. For temperatures above ~22°C, the feels-like temperature is generally higher than the measured temperature, likely due to humidity effects increasing heat perception. Conversely, for temperatures below ~16°C, the feels-like temperature tends to be lower than the measured temperature, indicating colder perceived conditions caused by factors such as wind chill.
6. The spread (dispersion) of feels-like values increases at both high and low temperature extremes, while mid-range temperatures show relatively low variability. This suggests that environmental factors influencing perceived temperature become more significant under extreme weather conditions.

### Assumptions