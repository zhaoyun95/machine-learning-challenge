# machine-learning-challenge
Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.
In this homework assignment, you will need to:

- Preprocess the raw data
- Tune the models
- Compare two or more models

### dataset
https://www.kaggle.com/nasa/kepler-exoplanet-search-results

### column definition
https://exoplanetarchive.ipac.caltech.edu/docs/API_kepcandidate_columns.html

### Results
* svm model
confirmed cases: precision = 38%; recall = 46%

* deep learning model
confirmed cases: loss = 70%; accuracy = 68%

Both models are not that good, they did not reach 85% accuracy.  Comparatively, deep learning model is better (68% > 46%).

