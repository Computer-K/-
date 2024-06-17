1.项目名称：基于Transformer的机器阅读理解

2.项目目标：
构建片段抽取式的机器阅读理解模型，对给定文本材料，以及基于材料的一个问题，让机器在阅读文章后为问题寻找答案。
3.编程语言：Python
4.主要模型框架：Transform、hfl/chinese-macbert-base。
5.数据收集与预处理：加载数据、使用AutoTokenizer进行分词、序列填充、裁剪等操作。
6.模型构建与训练：TrainingArguments，配置Trainer。
7.模型评估与预测：模糊匹配度F1、使用pipeline对模型进行测试。
8.项目成果：
我构建机器阅读理解模型模型，实现对目标文本的理解，获得我们所需的信息。

项目具体流程步骤：
第1步:导入相关包。训练导入Datasets包和TansFormers模型
第2步:数据加载。加载"cmrc2018"中的数据集。计算机理解和生成对文本的精确回答。
第3步：数据预处理。
第4步：加载chinese-macbert-base模型。
第5步：配置TrainingArguments，配置Trainer。
第6步:模型训练。
第7步:模型预测。使用pipeline对模型进行测试。
