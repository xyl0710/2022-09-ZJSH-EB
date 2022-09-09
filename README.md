# 2022-09
东证期货-中基石化需求对接

# 本项目各文件介绍
## eb_data.csv
为基于中基石化提供数据手动整合的数据，较为粗糙，大致分为daily，weekly，monthly数据
## 数据处理-EB.ipynb
基于eb_data数据集作简单合并
## df_eb.csv
由数据处理-EB.ipynb文件合并之后的数据集
## EB_Backtest.ipynb
回测文件，包括数据处理、回归、结果分析
