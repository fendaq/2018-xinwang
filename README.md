# 2018-新网银行杯Top1方案
## 基于集成学习的信用风险预测模型
   本次比赛通过机器学习和数据挖掘技术定量分析信用风险，给出每个样本的预测结果。首先，研究了违约客户和履约客户这两批客户的特征，其次，将机器学习领域比较流行的集成学习模型应用于信用风险评估领域，并利用主流的模型性能评价指标评价模型。在比赛中，对类别型数据进行哑编码，并搭建自编码网络提取特征，利用特征相关性，特征重要性，information value三个方法筛选特征，最后，选取基于加权平均法的集成学习模型和类别分布不平衡环境下基于加权平均法的半监督集成模型对数据进行建模，并使用AUC作为模型性能的具体评价指标，通过两种参数调节方法优化模型。在测试数据集上应用，竞赛结果验证了所构建的集成系统泛化能力较强，模型复杂度适中。  
## 模型一示意图如下：
![基于加权平均法的集成学习模型](https://github.com/CuiNing6/2018-xinwang/blob/master/img/method1.PNG)
## 模型二示意图如下：
![基于加权平均法的集成学习模型](https://github.com/CuiNing6/2018-xinwang/blob/master/img/method2.PNG)

###########################  
先写这么多，后续再添加内容。   
###########################

欢迎各位大佬批评指正  
如果发现错误，请及时与我联系  
邮箱：ning_cui@foxmail.com
