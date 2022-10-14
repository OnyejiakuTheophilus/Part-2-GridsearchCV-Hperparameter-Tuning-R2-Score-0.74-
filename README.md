# Part-2-GridsearchCV-Hperparameter-Tuning-R2-Score-0.74-
This is a sequel to [Part 1](https://www.kaggle.com/code/theophilusonyejiaku/part-1-gridsearchcv-hperparameter-tuning-r2-0-5), which involved the tuning of models using the `GridSearchCV`. At the end of the [Part 1](https://www.kaggle.com/code/theophilusonyejiaku/part-1-gridsearchcv-hperparameter-tuning-r2-0-5), we were only able to achieve a metric score of `0.5` (**50% accuracy**); this is so because we did not check for outliers and did not consider some feature engineering on our data.

In this **"Part 2"**, we take a closer look at our data and did some proper cleaning, outliers detection and removal (the unwanted ones) and repeated the same tuning process using the `GridSearchCV` like we did in [Part 1](https://www.kaggle.com/code/theophilusonyejiaku/part-1-gridsearchcv-hperparameter-tuning-r2-0-5). Fortunately, we got a better improvement in our models' metrics scores as shown in the table below:

|Model|R Squared value|
|----|----|
|Random Forest|0.745351|
|XGB|0.694323|
|kneighbor|0.603231|
|Decision Tree|0.582967|
|Lasso|0.173845|
|Linear Regression|0.173824|
