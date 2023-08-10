Regression model, make estimated calculation of relation betewen dependent and independent variables. Three prominent regression models are linear, multi and polynomial regression model


Simple Linear Regression Model
- finds a relation between single label(output) and single feature(input)
- calculates two coefficient i.e. slope and intercept
- general mathematical equation: is y = β₀ + β₁x + ε
- y = label, β₀ = y intercept, β₁ = slope, x = feature, ε = error/residual
- easy to extrapolate data on extended ranges of X values
  

Multiple Linear Regression Model
- establishes relation between single dependent(label) variable and 2 or more independent(feature) variable
- calculates intercept, slopes for each independent variable(feature)
- general equation is: y = β₀ + β₁ + β₂x₂ + ... + βi xiₖ + ε
- β₀ = y intercept, β₁ = slope of x₁, βi = slope of xi
- cannot be used to visualized on 2D scatter plot as therre are more than one independent variable


Polynomial Regression Model
- makes relation between label and feature usinf curves, i.e. nth degree of polynomial
- general equation is: y = β₀ + β₁x + β₂x² + β₃x³ + ... + βᵏxᵏ + ε
- β₀,β₁,β₂,β₃ = coefficient of polynomial, k = degree of polynomial
- extrapolated data is poor on extended ranges of X values, as the curvilinear relation is only made for trained dataset


 R² (R-squared)
- statistical metric, which porvides how well a model has predicted uknown value using known independent value on a scale of 0 - 1
- R-squared = 0: model does not explain any of the variability in the dependent variable
- R-squared = 1: model perfectly explains all the variability in the dependent variable
- one limitation is that it only works on trained dataset and not on unseen data, for that P value was introduced


# Regression-models-For-ML
