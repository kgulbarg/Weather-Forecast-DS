## Forecasting Target Selection

Weather is inherently a multivariate phenomenon rather than a single measurable quantity. Variables such as temperature, humidity, atmospheric pressure, precipitation, cloud cover, and wind conditions are physically interconnected and together describe the overall state of the atmosphere.

Initially, the possibility of forecasting a *composite weather representation* was considered. However, predicting an abstract combined weather variable would require a more advanced multivariate or coupled forecasting framework capable of simultaneously modeling complex dependencies among multiple atmospheric variables.

Another forecasting formulation explored was weather-condition classification using the `condition_text` feature, since it provides a broader semantic description of overall weather conditions rather than representing a single atmospheric measurement.

* a large number of categorical weather states,
* significant class imbalance,
* and inconsistencies in condition labels.

To maintain interpretability and enable a clear comparison between forecasting techniques within the scope of this assessment, the problem was therefore simplified to forecasting a single continuous target variable:

* `temperature_celsius`

At the same time, other weather-related variables — including humidity, pressure, cloud cover, precipitation, and wind measurements — are retained as predictive input features to preserve the multivariate nature of the dataset.

This formulation:

* simplifies model evaluation and comparison,
* improves interpretability of forecasting performance,
* while still leveraging relationships among multiple atmospheric variables through feature engineering.

Although temperature serves as the primary forecasting target, the remaining weather variables continue to play an important role during exploratory data analysis, correlation analysis, and anomaly detection due to their strong interdependent behavior.
