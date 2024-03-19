# 代码文档: Gemma—角色刻画微调

## 1. 概述
此项目利用Lora微调gemma模型使其适用于小说角色刻画，用以后续小说角色扮演起到重要作用。以蛊真人为例，小说的角色是随着剧情的增加不断成长的，一个固定的角色刻画在很多时候是不合理的，所以由此产生了这样一个需求，此代码探讨的便是如何保证随剧情发展改变角色的刻画。

## 2. 安装和依赖项
为了使用Gemma-角色刻画微调，你需要做以下准备

### 2.1 安装Python和相关依赖项
在代码中已经保留了依赖库安装

### 2.2 下载Gemma模型
Gemma 是先进的轻量级开放模型系列，采用了与创建 Gemini 模型相同的研究和技术。受到 Gemini 的启发，Google DeepMind 和 Google 其他团队合作开发了 Gemma，下载Gemma 需要申请Gemma api，并且在lora_gemma.ipynb和start-gemma-lora-model.ipynb中填写你的huggingface token。

## 3. 使用方法
以下是使用基本步骤：

### 3.1 准备输入文本
本项目以《蛊真人》为例，可以使用Data_Annotation_Aids.ipynb辅助进行数据标注。

### 3.2 运行代码
使用您喜欢的Python开发环境（如Jupyter Notebook、PyCharm等），打开提供的代码文件。在代码中，您需要进行以下设置：

## 4. 示例和演示
为了帮助您更好地理解gemma-Lora——角色刻画微调的使用，我们提供了一些示例段落。您可以将这些段落作为输入，运行代码并观察输出结果。

示例数据为output_2048.csv

## 5. 注意事项
在运行代码之前，请注意显卡显存最低要达到24GB，数据集最好不要超过2048。


## 6. 参考和致谢
- Gemma-2b-it：[链接](https://huggingface.co/google/gemma-2b-it)
