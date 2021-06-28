We need to use the same linear regression formula and then apply the y value to a sigmoid function. Apply the result back in the linear regression formula to obtain logistic regression.

y = b0 + b1x # Linear regression 

p = 1/(1 + e-y) # Sigmoid Function 

ln(p/(1-p)) = b0 + b1x #Logistic regression
