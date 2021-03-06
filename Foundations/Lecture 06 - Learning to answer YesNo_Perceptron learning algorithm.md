## Perceptron Learning algorithm (PLA)
* Find a perceptron
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/5_3_1.jpg)<br/>
<br>How do we find a best hypothesis? We want to know f(x) but we usally don't know it. We can find a "g" that may approximate "f", then we put Data(D) into g, if the y that generates by g matched the y in Data(D), so we can say "g" is close to "f" (or the same).<br/>
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/5_4.jpg)<br/>
* start from w0, and "correct" its mistakes on D
* Groud truth y=+1 but we got y=-1, which means we should minimize the included angle between w and x, we can modify w into w+y.
* Groud truth y=-1 but we got y=+1, which means we should enlarge the included angle between w and x, we can modify w into w+y.
* 以內積來說，兩向量 __夾角變小__ ，其 __值會變大__ ； __夾角變大__ ，其 __值會變小__  
## Cyclic PLA
* How do we make sure the PLA algorithm is great?
> We can put each data into g that generated by data, then check if the y generated by g matched the y in data until a full cycle of not encountering mistakes.
## The prococedure of how to find a best perceptron
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/5_5.jpg)<br/>
* There is no line at the beginning.
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/5_6.jpg)<br/>
* Update 1:Start from a central point (origin), then we find x1 and add a line (法向量, normal vector) to origin . 
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/5_7.jpg)<br/>
* Update 2:A black circle is in the wrong side. Original we should change the normal vector from red line to purple one by minimizing the included angle.
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/5_8.jpg)<br/>
* Update 3:A black X is wrong. We should change the normal vector from red line to purple one by enlarging the included angle.
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/5_9.jpg)<br/>
* Update 4: continue updated the line.
<br>![image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/5_10.jpg)<br/>

## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)


<!-- ref
http://naivered.github.io/2016/07/05/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L2-Notes-1/

-->
