## Trainng versus Testing

### Effective number of Hypotheses

* Dichotomy:Generate different kinds of (OOXX),(OXOX)...
* H (x1,x2,x3,....xn):Put different kinds of dichotomy together
* Hypothesis set:
1. Each hypothesis can get all inputs from space
2. Number of hypothesis can be infinite
* Dichotomy H:
1. Each dichotomy H only get N specific inputs from space
2. The size of dichotomy is 2 to the power of N
* Let's see if Dichotomy H can replace M inHoeffding’s Inequality
* |H(x1,x2,,,,xn)| depend on x1,x2,...xn. 
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/19_1.jpg)<br/>
<br><br/>
* Growth function: remove dependence by taking max of all possible (x1,x2...), that formalizes the number of "effective" hypotheses in a hypothesis set
* How to calculate growth function?
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/19_2.jpg)<br/>
<br><br/>
* Hypothesis is the threshold(+1:O,-1:X, this hypothesis also called positive rays)
* For this case, we have N+1 kinds of dichotomy
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/19_3.jpg)<br/>
<br><br/>
* Growth function for positive intervals
* positive intervals:C(N+1,2) represents any two points can be a positive interval)
* +1: all x
* Above we mentioned two examples of Mh(N), and m can replace the formula M in Hoeffding, so the prob(BAD) would be very small
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/19_4.jpg)<br/>
<br><br/>
* Convex: 凸
* How to calculate growth function for convex?

<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/19_5.jpg)<br/>
<br><br/>
* We can put circle in each angle on the Polygon (ex:three is for triangle, four is for rectangle). The growth function is Mh(N)=2 to the power of N
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/19_6.jpg)<br/>



 
## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
http://naivered.github.io/2016/08/13/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L5-Notes-1/
https://cynthiachuang.github.io/Machine-Learning-Foundations-Study-Notes-Mathematical-Foundations-Week2/?view
-->
