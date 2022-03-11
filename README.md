# Capstone-Project-II-Polynomial-regression

# =================  Polynomial Regression ===================

# Thus far, we have assumed that the relationship between the explanatory
# variables and the response variable is linear. This assumption is not always
# true. This is where polynomial regression comes in. Polynomial regression
# is a special case of multiple linear regression that adds terms with degrees 
# greater than one to the model. The real-world curvilinear relationship is captured
# when you transform the training data by adding polynomial terms, which are then fit in
# the same manner as in multiple linear regression.

# We are now going to us only one explanatory variable, but the model now has
# three terms instead of two. The explanatory variable has been transformed
# and added as a third term to the model to captre the curvilinear relationship.
# The PolynomialFeatures transformer can be used to easily add polynomial features
# to a feature representation. Let's fit a model to these features, and compare it
# to the simple linear regression model:
