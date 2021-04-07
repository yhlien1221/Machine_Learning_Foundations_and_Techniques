## Non-Separable data
### Concerns of PLA
* PLA is not practical in real world data. Most of data are non-linear separable and PLA won't be halted in non-linear separable data
* PLA takes very long time if the linear separable is too big
### PLA should be modified 
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/8_1.jpg)<br/>
* The best line for noise data is that the line with minimal errors
* This question is NP-hard, we can't get answer directly
* We can use approximate method to get a aprroximate wg, this is Pocket algorithm
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/8_2.jpg)<br/>
* It's an imporved alorithm to use find errors in a random way and correct it.
* If w (t+1) makes fewer errors than w hat, replace w hat by w (t+1) until enough interations.
* Return w hat (called W pocket) as *g*

## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
http://naivered.github.io/2016/07/05/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L2-Notes-1/
https://cynthiachuang.github.io/Machine-Learning-Foundations-Study-Notes-Mathematical-Foundations-Week2/?view
-->
