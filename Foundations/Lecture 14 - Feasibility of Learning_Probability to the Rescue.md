## Feasibility of learning

### Probability to the rescue
#### Statistics 101: Inferring Orange Probability
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/14_1.png)<br/>
* Probability of v is known in sample
* Probability of u is unknown in out-of-sample

#### Possible v.s. Probable
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/14_2.png)<br/>
* In most situations, v will be closed to u.

#### Hoeffding's Inequality
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/14_3.png)<br/>
* N:the number of sample
* ∈:threshold of difference between v and u
* **PAC**has high probability is correct
> probably : high probability (1-2exp(-2∈2N)
> approximatedly : error less than ∈

<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/14_4.png)<br/>
* if large N or large ∈ then P[|v-u|>∈] will be smaller and P[v≈u] will be bigger. 

 
## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
http://naivered.github.io/2016/07/05/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L2-Notes-1/
https://cynthiachuang.github.io/Machine-Learning-Foundations-Study-Notes-Mathematical-Foundations-Week2/?view
https://hackmd.io/@johnnyasd12/BJ9bqqevD/https%3A%2F%2Fhackmd.io%2F%40johnnyasd12%2FSy1zu2fTS
-->
