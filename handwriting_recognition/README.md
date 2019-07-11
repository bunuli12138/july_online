## 简介
七月在线网站‘手写字体识别’比赛

## 目录
[Data](Data)   数据集  
[Module](Operate/Module)   需要调用的模块  
[Operate](Operate)   操作文件夹  
[Result](Result)   可以提交的结果文件夹

## 数据集格式
>train_july.csv
- 0-783  图像每个像素的像素值
- label 图像的标签(数字)
- 训练集总共有六万张图片

> test_july.csv:
- index 测试图像的索引
- 0-783 图像每个像素的像素值
- 测试集总共有一万张图片

> sample_submission_fan.csv:
- index 测试图像的索引
- label  预测结果

| index | label |
| --- | --- |
| 0 | 0 |
| 1 | 0 |
| 2 | 0 |

## others
> 变量命名规则
