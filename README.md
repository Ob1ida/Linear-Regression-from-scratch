# Linear Regression From Scratch
--------------
## What is linear regression?
**Linear Regression** is a method userd to degine a relationship between a dependent variable (**Y**) and independent variable (**X**).

![1_nejpuvlh1MbMGQtve_1ztQ](https://github.com/user-attachments/assets/ffd25590-b01c-45a3-aabf-356f558e5b3c)

where **y** in the dependent variable , **m** is the scale factor or coefficient,**b** being the bias coefficient and **X** is the independent variable.
our goal is to find the best fit for **X** and **Y** wich estimates the relationship between **X** and **Y**.
but how do we find these coefficients?
that leads us to **Ordinary Least Mean Square Method**

## Ordinary Least Mean Square

<div align="center">
  <img src="https://github.com/user-attachments/assets/d8985f35-e14f-42a2-8a3d-067e7b14a5fe" alt="fittedLine">
</div>

The line seen in the graph is the actual relationship we going to accomplish,
And we want to minimize the error of our model.
<div align="center">
  <img src="https://github.com/user-attachments/assets/f1992368-5598-46da-9a8f-a828fe0420c8" alt="fittedLine">
</div>

**Ordinary least Mean Square** is a method that reduce the sum of the error of each point (**r**) 

![1_XTTjSJv7nogDk-Us9zWvRw](https://github.com/user-attachments/assets/f17e0784-0795-4c37-863a-acdbee592a9b)

ri = Distance between the line and ith point.

n =Total number of points.

We are squaring each of the distance's because some points would be above the line and some below.
To minimize the error of our linear model we can use this formula:

<div align="center">
  <img src="https://github.com/user-attachments/assets/ac2a90e5-e9d2-48c3-ba78-e1c3cf0de9b2" alt="fittedLine">
</div>

where **x¯** is the mean of the input variable **X** and **y¯** being the mean of the output variable **Y**.
