# Regulexa

Regulexa is a Python-based project designed to demonstrate and compare different regularization techniques used in machine learning: Ridge, Lasso, and Elastic-Net. Regularization helps to prevent overfitting and improves the generalization of models by adding a penalty term to the loss function. This project includes visualizations and performance comparisons for these techniques, making it a valuable resource for data science enthusiasts and machine learning practitioners.

## Regularization Techniques

1. Ridge Regression
- Ridge regression adds a penalty equal to the square of the magnitude of coefficients. It helps to reduce model complexity and multicollinearity.
- Penalty: α * ||w||₂² (L2 norm)
- Shrinks coefficients towards zero but never sets them exactly to zero.

2. Lasso Regression
- Lasso regression adds a penalty equal to the absolute value of the coefficients. It performs both variable selection and regularization.
- Penalty: α * ||w||₁ (L1 norm)
- Can shrink some coefficients to exactly zero, effectively performing feature selection.

3. Elastic-Net Regression
- Elastic-Net combines both Ridge and Lasso penalties.
- Penalty: α * [(1 - λ) ||w||₂² + λ ||w||₁]
- Suitable for datasets with correlated features and when feature selection is required.
