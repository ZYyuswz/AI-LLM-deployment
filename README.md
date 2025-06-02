# AI-LLM-deployment
同济大学软件工程专业人工智能导论大模型部署
# 项目说明文档目录
**详情请见hw4.pdf**
## 人工智能导论 —— 大语言模型部署

**姓名：赵诣**   
**专业：软件工程**  
**指导教师：曾进**  
**2024-2025学年第二学期**

## 1. 部署步骤与完成证明

## 1.1 登录魔搭平台，获得计算资源，启动notebook。

CPU环境下免费无限制使用，GPU环境下免费使用36h
本项目利用CPU环境与GPU环境均已搭建成功，除GPU环境在输出时用时略少外无区别，一般情况下CPU环境输出下面提到五个问题的答案时间也不会超过2min。
## 1.2 环境配置

## 1.2.1 打开terminal（终端命令行环境）

## 1.2.2 手动下载conda环境

## 1.2.3 激活环境

## 1.2.4 安装相关依赖

包括：
```bash
Pip  install  \"intel-extension-for-transformers==1.4.2"\"neural-compressor==2.5"\"transformers==4.33.3"\"modelscope==1.9.5"\"pydantic==1.10.13"\"sentencepiece"\"tiktoken"\"einops"\"transformers_stream_generator"\"uvicorn"\"fastapi"\"yacs"\"setuptools_scm"
Pip  install  \torch==2.3.0+cpu\torchvision==0.18.0+cpu\--index-urlhttps://download.pytorch.org/whl/cpu
安装fschat（需要启用PEP517构建）pip install fschat--use-pep517
```

## 1.3 部署大模型

## 1.3.1 下载大模型到本地

切换到数据目录：cd /mnt/data
分别下载两个大模型
git clone https://www.modelscope.cn/ZhipuAI/chatglm3-6b.git

git clone https://www.modelscope.cn/qwen/Qwen-7B-Chat.git


## 2. 大模型问答测试结果

## 2.1 编写测试脚本
先切换到工作目录，再编写测试脚本。

## 2.2 运行脚本，进行两个大模型的问答测试

## 3.大模型横向对比分析

## 3.1 横向对比分析：

## 3.2 模型优缺点总结

## 3.3 适用场景建议


