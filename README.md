# tcmrie
## What is tcmrie?
tcmrie是一个用于指导大语言模型选择的，针对中医医案信息抽取任务的评估基准。它可以评估不同LLM在中医医案信息抽取任务上的性能。

该评估基准的数据集来自中医专业人员审核，对于评估指标，我们采用其他信息抽取任务常用的评估指标并加以改进。

![image](https://github.com/medinfox/tcmrie/blob/main/PNG/workflow.png)

## How to use tcmrie？
将repo克隆到本地，然后运行

~~~
pip install -e.
~~~

·对于使用在线大模型服务，需要在endpoint和api_key中填入对应模型的端口，和自己注册的密钥即可使用

·对于本地模型则需要封装成具有OpenAI兼容接口的大语言模型，然后调用。

## What can you get from tcmrie?
使用tcmrie，你可以得到不同大语言模型在意an信息抽取任务上的效果，并对他们进行比较。

下图展示了部分知名模型在tcmrie上的效果

![image](https://github.com/medinfox/tcmrie/blob/main/PNG/results%20for%20some%20llms.png)
