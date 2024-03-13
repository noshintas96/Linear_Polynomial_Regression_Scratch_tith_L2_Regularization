# Linear and Polynomial Regression from Scratch with L2-Regularization

In this project, we aim to implement linear and polynomial regression of 2nd, 3rd, and 4th order from scratch, and apply L2-regularization to the 4th-order polynomial regression. We will perform these tasks using training data and evaluate the performance using different regularization parameters.
Implementation Overview:

## Linear and Polynomial Regression:
        We implement linear and polynomial regression models of 2nd, 3rd, and 4th order.
        Synthetic data is generated for training and testing the models.

## L2-Regularized Polynomial Regression:
        We extend the polynomial regression to include L2-regularization.
        Weight vectors are calculated for different regularization parameters (λ values).
        Training and test errors are calculated for each λ value.
        Train and test errors are plotted as a function of λ.

## Cross-Validation:
        We perform five-fold cross-validation on the training data.
        Training and validation sets are created for different combinations of the data.
        Weight vectors and validation errors are calculated for each λ value.
        Average validation error is calculated as a function of λ.

## Selection of Best λ:
        We compare the performance of different λ values based on average validation error.
        The best λ value is selected based on the lowest average validation error.

## Plotting Regression Line:
        We use the best λ value to calculate the predicted y values for a new input vector.
        The L2-regularized 4th-order polynomial regression line is plotted using the newly constructed input vector and predicted y values.

## Results:

### Best λ for L2-Regularization:
        For 4th-order polynomial regression, the best λ value is determined through cross-validation.
        The selected λ value is different from the one obtained without cross-validation.

### Model Evaluation:
        Train and test errors are compared for different λ values.
        The performance of the model with the selected λ value is evaluated based on test error and its relation to the training error.

### Visualization:
        Regression lines for the best λ value are plotted to visualize the fitted model.

## Conclusion:

    The best λ value obtained through cross-validation provides improved performance compared to a single fixed λ value.
    By applying L2-regularization, we achieve better generalization and avoid overfitting.

