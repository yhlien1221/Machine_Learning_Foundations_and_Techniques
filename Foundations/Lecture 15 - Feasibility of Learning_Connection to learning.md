## Feasibility of learning

### Connection to Learning
* The example of bin can be connected to learning
* In leanrnig, we like to know if h(x) = target f(x)
* x is a data from X
* *h* is **wrong** -> h(x) is not equal to f(x)
* *h* is **wrong** -> h(x) is equal to f(x)
* Check error of h on D
* If large N, then we can infer the error rate of h in whole data(based on Hoeffding’s inequality)
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/15_1.png)<br/>
* E out is whole data, E in is sample data N
* E in (h) denotes that the prob of h(x) != f(x) in whole data
* E out (h) denotes that the prob of h(x) != f(x) in sample N
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/15_2.png)<br/>
* If N large, we can infer that E in (h) is probably close to E out (h) (Based on Hoeffding’s inequality)
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/15_3.png)<br/>
### Verification of One h
* In general, h(x) will be picked by algorithm A and make sure E in(h) is smallest among all h.
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/15_4.png)<br/>
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/15_5.png)<br/>


 
## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
http://naivered.github.io/2016/07/05/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L2-Notes-1/
https://cynthiachuang.github.io/Machine-Learning-Foundations-Study-Notes-Mathematical-Foundations-Week2/?view
-->
