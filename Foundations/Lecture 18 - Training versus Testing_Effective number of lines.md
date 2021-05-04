## Trainng versus Testing

### Effective number of lines
* BAD event: Ein(h) and Eout is very far
* Hoeffding’s Inequality: give A freedom of choice to choose h. then calculate the prob of BAD event on a certain h, **union bound** is the union of all BAD events on all M 
* It's pointless if union bound is infinite due to infinite M

<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/18_1.jpg)<br/>
* The assumption of union bound is the dataset for BAD event in each h is different (no overlap). The assumption is wrong, dataset for BAD event is similar when two hypothesis are similar
* Union bound we learned earlier did not mention this concern (previous point) and it may cause over-estimating when M is infinite
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/18_2.jpg)<br/>
* To calculate the portion of overlapping, we can catogorize **infinite** h into **limited** catogories
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/18_3.jpg)<br/>
* How many kinds of lines?
- Data with one input: two lines (O,X)
- Data with two inputs: four types of lines. ( (O,X),(X,O),(O,O),(X,X))
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/18_4.jpg)<br/>
* How many kinds of lines for three inputs (four kinds of types)
* Any one of lines can't seperate those data in the same line.
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/18_5.jpg)<br/>
* How many kinds of lines for four inputs (fourteen kinds of types)
* 2*7 is because lines can be symmetric
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/18_6.jpg)<br/>
* Maximum kinds of lines is related to the number of input
* effective(N) must less than 2N (2 to the power of N) and N can replace M, then N can reduce exp value on the right of formula. The prob(BAD event) will be very small
* 
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/18_7.jpg)<br/>




 
## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
http://naivered.github.io/2016/08/13/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L5-Notes-1/
https://cynthiachuang.github.io/Machine-Learning-Foundations-Study-Notes-Mathematical-Foundations-Week2/?view
-->
