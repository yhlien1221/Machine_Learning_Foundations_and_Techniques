## Theory of generalization

### Bounding Function: Inductive Cases
#### Estimate B(N,k)
* In this section, we are going to fill the number of dichotomy for N > k
* B(4, 3) = 11 (Four data points and cannot shatter in any of 3 points)
* Try to find the relationship between B(4, 3) and B(
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/23_1.jpg)<br/>
<br><br/>
* Listed all the combination for B(4, 3) on the right side
* There are four paired marked in orange and three non-paird marked in purple when excluded x4
* Above can be expressed in a formula: B(4,3) = 2$\alpha$ + $\beta$
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/23_2.jpg)<br/>
<br><br/>
* dichotomies(x1,x2,x3) after excluding x4: $\alpha$ + $\beta$
* $\alpha$ + $\beta$ <= B(3,3)  (no shatter any 3 inputs in B(4,3) or it will violate the limitation of k=3)
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/23_3.jpg)<br/>
<br><br/>
* only focus on $\alpha$, $\alpha$ on (x1,x2,x3) with x4 paired
* $\alpha$ no shatter any 2
* $\alpha$ <= B (3,2)
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/23_4.jpg)<br/>
<br><br/>
* The proof of B(4,3) <= B(3,3) + B(3,2)
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/23_5.jpg)<br/>
<br><br/>
* now have upper bound of bounding function
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/23_6.jpg)<br/>
<br><br/>
* Upper bound of B(N,k)
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/23_7.jpg)<br/>
<br><br/>
* growth function will be poly(N) if this growth function has break point
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/23_8.jpg)<br/>
<br><br/>




## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
http://naivered.github.io/2016/08/13/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L5-Notes-1/
https://cynthiachuang.github.io/Machine-Learning-Foundations-Study-Notes-Mathematical-Foundations-Week2/?view
* break point at k=2 (N=2), the maximum combination at k=2 is 3.
* Any of two point cannot be shattered when N=3
-->
