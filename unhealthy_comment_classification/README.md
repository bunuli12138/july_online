## 简介
对于七月在线“不健康评论分类挑战-NLP”比赛的操作仓库  

## 目录
[Data](Data)： 数据集  
[Operate](Operate)： 操作文件  
[Result](Result)： 结果文件夹（可提交）  

## 数据集  
大量维基百科评论，这些评论已被人类评估者标记为不健康评论  

train： 
- 英文文本+6种该评论不健康类型的概率

提交格式：   

| id | toxic | severe_toxic | obscene | threat | threat | insult | identity_hate | 
| --- | --- | 


## 命名规则  
X/Y/train/test_Class_Description 或 Class_Description   
含义：     
- X：特征数据集，Y：标签，train：训练集，test：测试集  
- Class： 变量名称， Description：变量作用或来源简介  
- 逐步改变的变量，则后加 _Feature， 表示当前改变的来源特征  
- 以 _ 开头的变量表示不可变     
- 方法内的变量描述为简写首字母   
