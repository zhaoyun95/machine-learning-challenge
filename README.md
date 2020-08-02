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
* SVM model
- score: 0.74
- confirmed cases only
  kernel, precision, recall
  linear, 0.73, 0.90
  rbf, 0.53, 0.95
  poly, 0.51, 0.95



* Deep Learning model
confirmed cases: loss = 70%; accuracy = 68%

* Logistic Regression 
score: 77.13%

* Decision Tree model
score: 68%

* Random Forest model
score: 77.40%
- feature importance
 [(0.1686855604159887, 'koi_model_snr'),
  (0.16162502363875983, 'koi_prad'),
  (0.10905044931577702, 'koi_period'),
  (0.10568093894563921, 'koi_impact'),
  (0.10425958378206863, 'koi_depth'),
  (0.10027461918949472, 'koi_duration'),
  (0.09300511042263368, 'koi_insol'),
  (0.07963441337955753, 'koi_teq'),
  (0.07778430091008075, 'koi_time0bk')]


## Conclusion
Random Forest has the best score of 77.4%.  It is the best model based on my testing.
Random Forest is useful to point out the top 2 most important features are "koi_model_snr" and "Koi_prad".