# Linear Regression
Imagine you're trying to guess someone's height based on their shoe size. Linear regression is a tool that helps us do this kind of prediction. It   assumes there's a straight line relationship between the two things we're looking at (shoe size and height in this case). The tool then finds the  
best fitting line that minimizes the errors between our predictions and the actual heights.


## Simple Linear Regression
**Simple linear regression** is like drawing a straight line that best fits the heights of people with different shoe sizes. The steeper the slant of the line (slope), the more height typically increases with each larger shoe size. The point where the line crosses your height chart (intercept) tells you the predicted height if someone had a shoe size of zero (which wouldn't happen, but helps understand the position of the line). This helps us see the general trend of how shoe size might be linked to height.


Linear regression shows the linear relationship between the **independent** (predictor) variable i.e. X-axis and the **dependent** (output)         variable i.e. Y-axis, called linear regression. If there is a single input variable X(independent variable), such linear regression is **simple 
linear regression**.

![image](https://github.com/skaddy0310/Machine-Learning-Scratch/assets/26485697/2fec2243-2af5-419b-af45-012547fcfbb5)

The above graph represents the linear relationship between the dependent(Y) and independent(x) variables,and the blue line is said to be the best-fit line.


## Calculation

## Y<sub>i</sub> = W<sub>0</sub> + W<sub>1</sub> X<sub>i</sub>
