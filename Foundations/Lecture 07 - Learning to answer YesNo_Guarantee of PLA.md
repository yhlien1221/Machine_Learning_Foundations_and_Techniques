## Guarantee of PLA
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/7_1.jpg)<br/>
* How do we know whether data can be separated by a line? 
> __Linear Separability__
* Does PLA always halts if data is linear separable?

<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/7_2.jpg)<br/>
* Compare wt and wf
* "min" means is then nearest point of separable line
* the value of yn*wf*xn will more than 0 if it's correct 
* Two vectors can be compared by inner product. The value of inner product is bigger that means the included angle is smaller and the two vectors is closer.
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/7_3.jpg)<br/>
* The length of w may make the value of inner product longer.
* Wt changed only when mistake happened (see the formula in blue), so the value of inner product won't grow quickly
## After T times correction
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/7_4.jpg)<br/>
<br>We can get cos by their inner product. Maximum of cos is 1<br/>
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/7_5.jpg)<br/>
## PLA always halts on the premise that data is linear separable.

## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
http://naivered.github.io/2016/07/05/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L2-Notes-1/
https://cynthiachuang.github.io/Machine-Learning-Foundations-Study-Notes-Mathematical-Foundations-Week2/?view
https://www.twblogs.net/a/5b8868f12b71775d1cdc3b50
https://blog.csdn.net/zixiximm/article/details/53893790
-->
