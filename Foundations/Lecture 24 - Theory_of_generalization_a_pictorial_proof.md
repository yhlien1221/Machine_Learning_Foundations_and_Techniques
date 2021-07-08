## Theory of generalization

### A Pictorial Proof
#### Bad bound
* The final upper bound of growth function is poly, so can we put this into Hoeffding directly? No
* The following sections all about the proof of this formula 
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/24_1.jpg)<br/>
<br><br/>
* We are interested is the prob of bad
* Bad event: Ein and Eout is not close
* Bad data: For some h, it will happen bad event
* We hope the prob of bad data is low
* The growth function for Ein(h) is around N
* Eout(h) has infinite points, so we can't use it directly
* We need to change Eout with finite number of Eout
* we can use finite points (that is D' or ghost data) to esimate Eout (that is Ein')
* The graph in the right side, list all Ein on the graph and Eout is in the middle. It is possible that E'in and Ein are far away when samping E'in from green part
* That's why Eout can be replaced by E'in
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/24_2.jpg)<br/>
<br><br/>
* Infinite hypothesis can be categoried into mH(N) types, now we have D', so the total points is 2N.
<br>Hypothesis may be overlapped in this case, so the dichotomies will be mH(2N)<br/>
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/24_3.jpg)<br/>
<br><br/>
* We are going to calculate the difference between Ein and E'in.
1. Take 2N
2. Take N among 2N
3. Compare the mean of N with the mean of remainig N or the mean of 2N (by Hoeffding)
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/24_4.jpg)<br/>
<br><br/>

#### VC bound
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/24_5.jpg)<br/>
<br><br/>
* For 2D perceptrons, its break point is 4 which means its speed of growth function no more than O(N3)
* In 2D perceptrons, we pick the smallest Ein and Eout in hypothesis g would be the smallest when N is large enough

<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/24_6.jpg)<br/>
<br><br/>





## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
http://naivered.github.io/2016/08/13/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L5-Notes-1/
https://cynthiachuang.github.io/Machine-Learning-Foundations-Study-Notes-Mathematical-Foundations-Week2/?view
* break point at k=2 (N=2), the maximum combination at k=2 is 3.
* Any of two point cannot be shattered when N=3
-->
