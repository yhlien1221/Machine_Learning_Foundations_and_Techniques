# Perceptron Hypothesis Set
## Perceptron
<br> Continue example of credit card, we will use the perceptron to give out an algorithm.<br/>
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/5_1.jpg)<br/>
* Customers have different features, like salary or debt and that is a vector in x=(x1,x2....).
* Then we give weights to each feature, like w1, w2.... (also a vector)
* Then we do the inner product of features and weights, then we got score from each customer. We use the score to minus threshold then got output. 
* Approve credit if weighted score > threshold, deny credit if weighted score < threshold
* We can get a different hypothesis by changing threshold or weight. The hypothesis in this case is called __Perceptron__. 
## Threshold can be a part of vector by simplifying the formula (add w0,x0)
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/5_2.jpg)<br/>
* What do perceptron *h* "look like"?
## What do perceptron *h* "look like"?
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/5_3.jpg)<br/>
*Assume we have some features in a R2(二維) vector, then h(x) is a line. One side of the line is positive and another side is negative. It can separate data into credit (circle) or deny credit (X), so we can understand that __Perceptron__ is a linear (binary) classifiers.

## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)



<!-- ref
http://naivered.github.io/2016/07/05/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L2-Notes-1/

-->
