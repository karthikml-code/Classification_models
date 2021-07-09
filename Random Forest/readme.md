It mainly runs on Ensemble learning. It’s basically doing multiple decision trees to build a random state.

Steps involved as follows:

step 1: Pick at random K data points from the Training set.
step 2: Build the Decision Tree associated to these K data points.
step 3: Choose the number Ntree of trees you want to build and repeat Steps 1 & 2
step 4: For a new data point, make each one of your Ntree trees predict the category to which the data points belongs, 
and assign the new data point to the category that wins the majority vote.
