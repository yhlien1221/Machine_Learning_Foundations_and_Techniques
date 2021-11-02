## The VC Dimension

### Interpreting of VC Dimension
* epsiloin represents the generalization ability of h
- the smaller epsilon, the better generalization ability it has.
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/28_1.jpg)<br/>
<br><br/>
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/28_2.jpg)<br/>
<br><br/>
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/28_3.jpg)<br/>
<br><br/>
* We already have the boudary of Eout and we care more about the possible upper bound of Eout
* The red part in below is model complexity.
* Complexity is based on N (sample size), H(dvc), eplison, Eout is based on Ein
* Below is the relationship between model complexity, Eout, Ein and dvc
* Power H not always good
* dvc bigger, Ein smaller and Omega bigger (complicated)
* dvc smaller, Ein bigger and Omega smaller (simple)
* With dvc increasing, Eout will be reduced then increased
* The optimal number of feature (dvc) is very important to get minimum Eout

<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/28_4.jpg)<br/>
<br><br/>
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/28_5.jpg)<br/>
<br><br/>

* Sample Complexity
* How many sample size does it need if dve was selected
* N = 29300 that meets the delta = 0.1. N is 10,000 folds of dvc. In fact, 10 folds of dvc is enough for practice rule of thumb.
* N is huge due to the looseness of VC bound.
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/28_6.jpg)<br/>
<br><br/>
* VC bound is hardly better, and "similarly loose for all models
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/28_7.jpg)<br/>
<br><br/>
<br>
### Summary
* VC dimension:non-break point
* VC dimension of perceptrons is d+1 under d dimension
* the optimal dvc is very important to get minimum Eout and better generalization ability

## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
https://qiubite31.github.io/2017/08/16/Machine-Learning-Foundation-7/
https://medium.com/%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92%E5%9F%BA%E7%9F%B3%E7%B3%BB%E5%88%97/%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92%E5%9F%BA%E7%9F%B3-4-vc-dimension%E5%92%8C%E6%A8%A1%E5%9E%8B%E8%A4%87%E9%9B%9C%E5%BA%A6-5398ed1c8a5e
https://iter01.com/92.html
-->
