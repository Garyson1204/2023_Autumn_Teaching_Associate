# 2023_Autumn_Teaching_Associate

## 第一次作业

基于给出的 Breast Cancer Wisconsin (Diagnostic) Dataset 搭建一个简单的分类器(如，朴素贝叶斯分类器、最近邻分类器)，实现对乳腺肿瘤良恶性的预测。

 **要求**：

1. Python实现；
2. 利用可视化对各个特征和乳腺癌良恶性的关系进行分析或可视化预测结果。

 **作业提交**：

- 代码、可视化结果打包发送至[sunhao0504@bupt.edu.cn](mailto:sunhao0504@bupt.edu.cn)
- 命名格式为姓名_学号， e.g. 张三_2020111234.zip
- 提交时间以邮件时间戳为准。 

### 数据集说明

**Attribute Information**:

1. ID number
2. Diagnosis (M = malignant, B = benign) 

3-12. Ten real-valued features are computed for each cell nucleus:

- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension ("coastline approximation" - 1)
