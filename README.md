# rule reduction in fuzzy neural network 

Runtime Reduction Of a RBF Fuzzy Neural Network by reducing number of rules using a Linear programming optimization approach
Runtime Reduction in Fuzzy Neural Network by reducing number of rules using an optimization approach

In this project we decreased number of rules in fuzzy neural network (FNN) by solving an optimization problem. this task is preformed for Regression and Classification (Binary /Multi class) problems. we used pulp library for the optimization problem task in Linear Programming (LP). in our approach we have absolute operation in the optimization function. but in LP we can't use absolute of a variable, so we redefine it as follow:


![](https://user-images.githubusercontent.com/50669689/137601017-a49fabb6-7641-4eb5-910b-bb964c066bf6.png){height="700px" width="400px"}

# Optimization functions:

1.**Regression:**
  
we have N training samples, so we write the optimization function as :

![image](https://user-images.githubusercontent.com/50669689/137600904-f7f783bb-e473-4914-ad0b-23c7e48c7251.png)


that 

![image](https://user-images.githubusercontent.com/50669689/137600905-af331c22-e075-4f06-82a8-571f1410834e.png)


and 

![image](https://user-images.githubusercontent.com/50669689/137600910-455cd1e8-aed3-438b-aead-7cff44a2885e.png)



