# Paper1
## 研究目的
1 构建一个PD预警模型，可以对肠道菌群样本进行疾病预测。\
2 构建一个功能基因预测模型，来预测疾病\
选择结构或者功能模型作为下面疾病的预测\
3 构建正常人肠道菌群年龄预测模型，并验证\
4 通过PD疾病预测人体衰老程度\

## 主要内容
SRP373424 PRJNA834801  
meta SRP373424(ncbi) 725samples  
特征 Group(Control[234],PD[491]),Age,Sex,饮食问卷等;USA,hsa  \

对结构细菌和功能作为特征。

### 机器学习
随机森林、线性回归、梯度提升，构建预测模型

### 年龄预测
#####男性\
######特征降维\
######构建模型\
#####女性\
######特征降维\
######构建模型\
#####混合\
######特征降维\
######构建模型\

30-90岁，两个分类，每10年龄一个段。构建男女分别模型，以及混合模型

已发表文章 Metagenomics of Parkinson’s disease implicates the gut microbiome in multiple disease mechanisms

# Paper2
## 研究目的
大多数研究PD人群与NC人群的预警模型来自于菌群，而菌群的功能是宏基因组的优势，是否可以通过菌群功能来更准确的构建更适合的菌群模型呢？构建基于多组学的机器学习是否可以提高PD机器学习预测的模型呢？
## 研究内容
[-] 构建PD人群与NC人群菌群(菌群特征来源于数据库比对)机器学习预测模型
[-] 构建PD人群与NC人群菌群(菌群特征来自于组装)机器学习预测模型
[-] 构建PD人群与NC人群基因机器学习预测模型
[-] 构建PD人群与NC人群代谢机器学习预测模型
[-] 构建PD人群与NC人群碳水化合物酶机器学习预测模型
[-] 构建PD人群与NC人群多组学机器学习预测模型
### 机器学习
随机森林、线性回归、梯度提升，构建预测模型
