## XGBoost Model

#### Gradient Boosting
* 이전 모형의 약점을 보완하여 새로운 모형을 순차적으로 적합한 뒤 이들을 선형 결합하여 얻어진 모형을 생성하는 지도 학습 알고리즘  
* $y_k = F_{prev}(x_k) + l \times h(x_k)$
* $h()$ : 실제값과 예측값의 차이를 줄여주는 함수
* $l$ : learning rate
* $F_m(x) = h_0(x) + l \times h_1(x_1) + \cdots + l \times h_m(x_m)$

##### Algorithm
1. 초기 모형은 상수로 설정한다.
   * $F_0(x) = \underset{\gamma}{\text{argmin}} \underset{i=1}{\overset{n}{\sum}}L(y_i, \gamma)$ 
2. $m = 1, \ldots, M$에 대하여 아래 순서를 반복한다.  
   (a) 유사 잔차(Pseudo Residual) 계산  
   * $r_{im} = -\frac{\partial L(y_i, F(x_i))}{\partial F(x_i)}_{F(x) = F_{m-1}(x)}$  
   (b)  
   (c)  
   (d)  
  
#### Tree Boosting 
#### End-to-End 


-----
Study Q&A
* XGBoost start at gradient boosting
* tree들을 합친게 boosting 
























