# rule reduction in fuzzy neural network 
Runtime Reduction Of a RBF Fuzzy Neural Network by reducing number of rules using a Linear programming optimization approach
Runtime Reduction in Fuzzy Neural Network by reducing number of rules using an optimization approach

In this project we decreased number of rules in fuzzy neural network (FNN) by solving an optimization problem. this task is preformed for Regression and Classification (Binary /Multi class) problems. we used pulp library for the optimization problem task in Linear Programming (LP). in our approach we have absolute operation in the optimization function. but in LP we can't use absolute of a variable, so we redefine it as follow:


![image](https://user-images.githubusercontent.com/50669689/137600824-1c23556b-a9d2-421b-a95d-d1b293ad1b08.png)

