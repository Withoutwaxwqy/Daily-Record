# GNSS Context-aware Theory
__For studies in GNSS context-aware__

# Context   
     
* [Airticals related to GNSS context-aware](###Airticals)     
* [Cluster analysis](###分类算法)
    
### Airticals
|name|decription|
|:-----|:---------|
|城市分类场景的GNSS 伪距随机模型构建及其定位性能分析|- [x]     将场景划分为|


**1.城市分类场景的GNSS 伪距随机模型构建及其定位性能分析**    
- [ ] read
- [ ] indicator analysis


GNSS Pseudorange Stochastic Model for Urban Classification Scenes and Its Positioning Performance
![image](https://github.com/Withoutwaxwqy/Daily-Record/assets/42163472/88126de5-6c3c-4be7-bd0f-448a8300e509)    


**2.不同观测环境中基于TEQC的GNSS数据质量分析**   
Quality analysis of GNSS data based on TEQC in different environments
![image](https://github.com/Withoutwaxwqy/Daily-Record/assets/42163472/107643a1-7f73-42b3-8145-c67ad2b101a1)    

**3.基于场景检测的城市环境 GNSS/INS组合定位方法研究**    
Research on GNSS/INS Integrated Positioning Method for Urban Environment Based on Context Aware    
论文将场景分为**室内外和室外有无遮挡**。    
第一阶段：场景建模训练阶段   
![image](https://github.com/Withoutwaxwqy/Daily-Record/assets/42163472/e874581b-ceb1-43da-a385-62c20c2925f5)   
第二阶段：   

![image](https://github.com/Withoutwaxwqy/Daily-Record/assets/42163472/4bf7d779-fc74-459a-983e-762b837a5437)    
比较新颖的点在于***卫星方位角空缺度***，这个衡量标准在其他地方也见到过。
![image](https://github.com/Withoutwaxwqy/Daily-Record/assets/42163472/80b067d0-e4d2-4de5-bbb9-b37ca28f1d51)


### 分类算法
![image](https://github.com/Withoutwaxwqy/Daily-Record/blob/main/picture/different%20classfication%20method.png)

- SVM
支持向量机（英语：support vector machine，常简称为SVM，又名支持向量网络）是在分类与回归分析中分析数据的监督式学习模型与相关的学习算法。   
公式见于[知乎SVM](https://zhuanlan.zhihu.com/p/49331510)   

- KMeans    
聚类是在事先并不知道任何样本标签的情况下，通过数据之间的内在关系把样本划分为若干类别，使得同类别样本之间的相似度高，不同类别之间的样本相似度低   


### 区分树荫和高架下场景
树荫可能是较长时间段的一段信号质量差周跳多，卫星在改方位上可能跳动的比较频繁，但是高架下，应该就接近于完全遮挡的环境
