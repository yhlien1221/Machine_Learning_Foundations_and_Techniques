## Theory of generalization

### Bounding Function: Basic Cases
* Bounding Function: the upper bound of growth function. In N points and break point = k, the maximum combination that cannot shatter any k points, it will be represented by B(N,k)
* Regardless of what kind of growth function can use this bounding function. For instance, B(N,3) is the upper bound for positive interval (k=3) and 1D perceptron(k=3) 
* Next we will check whether B(N,k) <= poly(N)?
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/22_1.jpg)<br/>
<br><br/>
* Table of bound function 
* B(N,k) = 2^N^ -1 for N=k
* For any B(N,1)=1, it only has one
* B(N,k) = 2^N^ for N <k, it won't reach k points and won't violate the limitation of break point
* B(N,k) = 2^k^ - 1 for N = k, it cannot shatter when k points
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/22_2.jpg)<br/>
<br><br/>





## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
http://naivered.github.io/2016/08/13/Study_Notes/Machine%20Learning%20Foundations/Machine-Learning-Foundations-L5-Notes-1/
https://cynthiachuang.github.io/Machine-Learning-Foundations-Study-Notes-Mathematical-Foundations-Week2/?view
* break point at k=2 (N=2), the maximum combination at k=2 is 3.
* Any of two point cannot be shattered when N=3
-->
