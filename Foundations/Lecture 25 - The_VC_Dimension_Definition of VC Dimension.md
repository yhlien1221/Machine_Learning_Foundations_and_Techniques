## The VC Dimension

### Definition of VC Dimension
* mH(N) with break point, then its growth function has the upper bound (bound function).
* The upper bound of this bound function is N^K-1^
* N(k-1) is much flexible than B(N,k)
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/25_1.png)<br/>
<br><br/>
* VC bound can be converted like below.

<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/25_2.png)<br/>
<br><br/>
* This inequality only related to k and N, then we only consider k value because N is large enough in most situations.
- if mh(N) breaks at k and N is large enough then this alorithm has good ability to generalization in Eout is similar to Ein.
- Algorithm picks a g with small Ein then the error rate of all data will be low (learned)
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/25_3.png)<br/>
<br><br/>
#### VC Dimension
* VC Dimension is to assume mh(N) has the maximum number of iputs of shatter (最大完全正確的分類能力)
* Shatter:listed all the combinations of inputs 
* dvc = 'minimum k' - 1
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/25_4.png)<br/>
<br><br/>
* VC Dimension in positive rays, positive intervals, convex sets and 2D perceptrons
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/25_5.png)<br/>
<br><br/>
* k can be replaced by dvc
<br>[image](https://github.com/yhlien1221/Machine_Learning_Foundations_and_Techniques/blob/main/Foundations/pic/25_6.png)<br/>
<br><br/>

## Reference:
1. Hsuan-Tien Lin - Machine Learning Foundations (機器學習基石)

<!-- ref
https://qiubite31.github.io/2017/08/16/Machine-Learning-Foundation-7/
https://medium.com/%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92%E5%9F%BA%E7%9F%B3%E7%B3%BB%E5%88%97/%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92%E5%9F%BA%E7%9F%B3-4-vc-dimension%E5%92%8C%E6%A8%A1%E5%9E%8B%E8%A4%87%E9%9B%9C%E5%BA%A6-5398ed1c8a5e
https://iter01.com/92.html
-->
