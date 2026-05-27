### Forecasting Target Selection

Weather is a multivariate phenomenon rather than a single measurable quantity. Features such as temperature, humidity, pressure, precipitation, cloud cover, and wind conditions are physically interconnected and collectively describe the overall weather state.

Initially, I considered the possibility of forecasting a "composite weather" representation. However, forecasting an abstract combined weather variable would require an advanced multivariate or coupled forecasting framework capable of modeling the dependencies between multiple atmospheric variables simultaneously.

However, to maintain interpretability and provide a clear comparison between forecasting techniques within the scope of this assessment, the forecasting task focuses primarily on a single target variable:

- `temperature_celsius`

while incorporating other weather-related variables such as humidity, pressure, cloud cover, precipitation, and wind measurements as predictive features.

This approach:
- simplifies model evaluation and comparison,
- enables clearer interpretation of forecasting performance,
- while still leveraging the multivariate nature of weather through the feature set.

Additional weather variables remain important during exploratory analysis and anomaly detection due to their interdependent behavior.