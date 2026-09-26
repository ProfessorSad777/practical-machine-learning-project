# Practical Machine Learning Course Project

Prediction assignment for the Johns Hopkins University Practical Machine Learning course.

- [View the rendered report](https://professorsad777.github.io/practical-machine-learning-project/)
- [R Markdown source](Prediction_Assignment_Writeup.Rmd)
- [Compiled HTML](Prediction_Assignment_Writeup.html)
- [Predictions for the 20 quiz cases](predictions.txt)

The analysis predicts the `classe` outcome in the Weight Lifting Exercise Dataset. After removing administrative and mostly missing fields, a random forest was trained on 52 sensor measurements. Model performance was assessed with five-fold cross-validation and a separate 25% stratified validation set.

The mean cross-validation accuracy was 99.27%. Accuracy on the untouched validation set was 99.59%, giving an estimated out-of-sample error of 0.41%.

The repository contains the complete R Markdown analysis and a compiled, self-contained HTML report for peer review.

## Data source

Velloso, E., Bulling, A., Gellersen, H., Ugulino, W., and Fuks, H. (2013). *Qualitative Activity Recognition of Weight Lifting Exercises*. Proceedings of AH 2013.
