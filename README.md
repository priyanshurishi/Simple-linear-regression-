# Simple-linear-regression-
Simple linear regression is an approach for predicting a response using a single feature.
It is assumed that the two variables are linearly related. Hence, we try to find a linear function that predicts the response value(y) as accurately as possible as a function of the feature or independent variable(x).
Let us consider a dataset where we have a value of response y for every feature x: 

![image](https://user-images.githubusercontent.com/76909600/149725730-88830aa4-2929-432c-b38d-8a41b9f432e0.png)

For generality, we define:
x as feature vector, i.e x = [x_1, x_2, …., x_n],
y as response vector, i.e y = [y_1, y_2, …., y_n]
for n observations (in above example, n=10).
A scatter plot of the above dataset will be given in the result of the code.

Now, the task is to find a line that fits best in the above scatter plot so that we can predict the response for any new feature values. (i.e a value of x not present in a dataset)
This line is called a regression line.
