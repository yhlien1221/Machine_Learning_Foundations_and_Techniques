## Trainng versus Testing

### Recap and Preview
* Recap those chapters we learned before
* The points of those chapters split to two central question
- Is Eout(g) close enough to Ein(g)?
- Is Ein(g) small enough
* M is the size of hypothesis
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/17_1.jpg)<br/>
<br><br/>
### Trade-off on M ((Hoeffding’s Inequality)
#### 1. can we make sure that Eout(g) is close enough to Ein(g)?
#### 2. can we make Ein(g) small enough?
###### Small M
1. the prob of **BAD** is small (2*M*exp(...))
2. we can't make Ein(g) small with too few choices
<br><br/>
##### Large M
1. the prob of **BAD** is large (2*M*exp(...))
2. we can make Ein(g) small enough with many choices
<br><br/>
###### use the right M (or H) is very important


 
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/17_2.jpg)<br/>



 
## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
http://naivered.github.io/2016/07/05/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L2-Notes-1/
https://cynthiachuang.github.io/Machine-Learning-Foundations-Study-Notes-Mathematical-Foundations-Week2/?view
-->
