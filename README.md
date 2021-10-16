# rule reduction in fuzzy neural network 

Runtime Reduction Of a RBF Fuzzy Neural Network by reducing number of rules using a Linear programming optimization approach
Runtime Reduction in Fuzzy Neural Network by reducing number of rules using an optimization approach

In this project we decreased number of rules in fuzzy neural network (FNN) by solving an optimization problem. this task is preformed for Regression and Classification (Binary /Multi class) problems. we used pulp library for the optimization problem task in Linear Programming (LP). in our approach we have absolute operation in the optimization function. but in LP we can't use absolute of a variable, so we redefine it as follow:

<img src="https://user-images.githubusercontent.com/50669689/137601017-a49fabb6-7641-4eb5-910b-bb964c066bf6.png" width="120" height="100">


### Optimization functions :

### 1.**Regression :**
  
we have N training samples, so we write the optimization function as :

<img src="https://user-images.githubusercontent.com/50669689/137600904-f7f783bb-e473-4914-ad0b-23c7e48c7251.png" width="200" height="230">


that 

<img src="https://user-images.githubusercontent.com/50669689/137600905-af331c22-e075-4f06-82a8-571f1410834e.png" width="150" height="80">


and 

<img src="https://user-images.githubusercontent.com/50669689/137600910-455cd1e8-aed3-438b-aead-7cff44a2885e.png" width="200" height="50">


### 2.**Binary Classification :** 

<img src="https://user-images.githubusercontent.com/50669689/137602457-a98372d0-cc68-4b25-9294-e1a00dd47f7e.png" width="200" height="240">



### 3.**MultiClass Classification :** 

<img src="https://user-images.githubusercontent.com/50669689/137602476-6c5e284e-2471-40ef-ae67-c6b6139df2bc.png" width="100" height="100">


that 

<img src="https://user-images.githubusercontent.com/50669689/137602480-49330113-2aa3-429e-b794-8aeb1421cb18.png" width="100" height="100">


