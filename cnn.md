## 13 卷积神经网络

### 13.1卷积神经网络的优化

#### 后向传播

#### 梯度下降法

#### Adam



### 13.1卷积神经网络正则化的相关技术

#### data augmentation

#### weight decay

#### dropout

#### normalization

![image-20210414110321086](C:\Users\yuanq\Documents\GitHub\Readinggroup\image-20210414110321086.png)

$\hat{x}_{i}=\frac{1}{\sigma_{i}}\left(x_{i}-\mu_{i}\right),\quad\mu_{i}=\frac{1}{m} \sum_{k \in \mathcal{S}_{i}} x_{k}, \quad \sigma_{i}=\sqrt{\frac{1}{m} \sum_{k \in \mathcal{S}_{i}}\left(x_{k}-\mu_{i}\right)^{2}+\epsilon}$



#### label smoothing

#### mixup

#### warmup

