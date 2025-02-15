# LLMs Interview 八股文

问题来源：[大模型（LLMs） 算法工程师相关的面试题](https://github.com/km1994/LLMs_interview_notes "大模型（LLMs） 算法工程师相关的面试题")

## 更新记录

- 2023.11.27 ： 15.token及模型参数， 16.tokenize分词
- 2023.11.25 ： 13.分布式训练
- 2023.11.23 ： 6.推理， 7.预训练， 8.评测，9.强化学习， 11.训练数据集，12.显存问题,14.agent
- 2023.11.22 ： 5.高效微调
- 2023.11.10 ： 4.LangChain
- 2023.11.08 ： 建立仓库；1.基础，2.进阶，3.微调

## 注意：

相关答案为自己撰写，若有不合理地方，请指出修正，谢谢！

## 目录

[1.基础](1.基础/1.基础.md "1.基础") 

[2.进阶](2.进阶/2.进阶.md "2.进阶")

[3.微调](3.微调/3.微调.md "3.微调")

[4.LangChain](4.LangChain/4.LangChain.md "4.LangChain")

[5.参数高效微调（PEFT）](5.参数高效微调（PEFT）/5.参数高效微调（PEFT）.md "5.参数高效微调（PEFT）")

- [5.1 基本概念](5.参数高效微调（PEFT）/1.基本概念.md "1.基本概念")
- [5.2 Prompting](5.参数高效微调（PEFT）/2.Prompting.md "2.Prompting")
- [5.3 Aadapter-tuning](5.参数高效微调（PEFT）/3.Aadapter-tuning.md "3.Aadapter-tuning")
- [5.4 LoRA](5.参数高效微调（PEFT）/4.LoRA.md "4.LoRA")
- [5.5 总结](5.参数高效微调（PEFT）/5.总结.md "5.总结")

[6.推理](6.推理/6.推理.md "6.推理")

[7.预训练](7.预训练/7.预训练.md "7.预训练")

[8.评测](8.评测/8.评测.md "8.评测")

[9.强化学习](9.强化学习/9.强化学习.md "9.强化学习")

[10.软硬件配置](10.软硬件配置/10.软硬件配置.md "10.软硬件配置")

[11.训练数据集](11.训练数据集/11.训练数据集.md "11.训练数据集")

[12.显存问题](12.显存问题/12.显存问题.md "12.显存问题")

[13.分布式训练](13.分布式训练/13.分布式训练.md "13.分布式训练")

- [13.1 概述](13.分布式训练/1.概述/1.概述.md "1.概述")
- [13.2 数据并行](13.分布式训练/2.数据并行/2.数据并行.md "2.数据并行")
- [13.3 流水线并行](13.分布式训练/3.流水线并行/3.流水线并行.md "3.流水线并行")
- [13.4 张量并行](13.分布式训练/4.张量并行/4.张量并行.md "4.张量并行")
- [13.5 序列并行](13.分布式训练/5.序列并行/5.序列并行.md "5.序列并行")
- [13.6 多维度混合并行](13.分布式训练/6.多维度混合并行/6.多维度混合并行.md "6.多维度混合并行")
- [13.7 自动并行](13.分布式训练/7.自动并行/7.自动并行.md "7.自动并行")
- [13.8 MOE并行](13.分布式训练/8.MOE并行/8.MOE并行.md "8.MOE并行")
- [13.9 总结](13.分布式训练/9.总结/9.总结.md "9.总结")

[14.agent](14.agent/14.agent.md "14.agent")

[15.Token及模型参数](15.Token及模型参数/15.Token及模型参数.md "15.Token及模型参数")

[16.tokenize分词](16.tokenize分词/16.tokenize分词.md "16.tokenize分词")

[17.位置编码](17.位置编码/17.位置编码.md "17.位置编码")

[18.Layer Normalization](18.Layer-Normalization/18.Layer-Normalization.md "18.Layer Normalization")

[19.激活函数](19.激活函数/19.激活函数.md "19.激活函数")

[20.加速](20.加速/20.加速.md "20.加速")

[21.Attention升级](21.Attention升级/21.Attention升级.md "21.Attention升级")

[22.幻觉](22.幻觉/22.幻觉.md "22.幻觉")

[23.思维链（COT）](23.思维链（COT）/23.思维链（COT）.md "23.思维链（COT）")
