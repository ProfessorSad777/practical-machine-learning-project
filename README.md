# Practical Machine Learning Course Project

Prediction assignment for the Johns Hopkins University Practical Machine Learning course.

- [View the rendered report](https://professorsad777.github.io/practical-machine-learning-project/)
- [R Markdown source](Prediction_Assignment_Writeup.Rmd)
- [Compiled HTML](Prediction_Assignment_Writeup.html)
- [Predictions for the 20 quiz cases](predictions.txt)

The analysis predicts the `classe` outcome in the Weight Lifting Exercise Dataset using 52 sensor measurements. A classification tree is compared with three random-forest settings using five-fold cross-validation. Both cross-validation and the holdout split keep participant/recording-window groups together, preventing readings from one window from entering both sides of a split.

The selected forest uses 14 candidate variables per split. Mean grouped cross-validation accuracy is 92.48%. Accuracy on 4,993 readings from 216 untouched validation windows is 95.61%, giving an estimated out-of-sample error of 4.39%. A window bootstrap gives an approximate 95% accuracy interval of 93.62% to 97.35%. The report discusses why these results do not establish performance for new participants.

The repository contains the complete R Markdown analysis, an HTML report compiled with knitr, and the 20 predictions in problem order. The writeup is under 2,000 words and contains one figure.

## Data source

Velloso, E., Bulling, A., Gellersen, H., Ugulino, W., and Fuks, H. (2013). *Qualitative Activity Recognition of Weight Lifting Exercises*. Proceedings of AH 2013.
