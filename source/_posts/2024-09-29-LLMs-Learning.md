---
layout: post
title: Learning "Build a Large Language Model (From Scratch)"
description: 学习《Build a Large Language Model (From Scratch)》一书
date: 2024-09-29 16:12:30 +0800
tags: CS-Learning
---

# Learning "Build a Large Language Model (From Scratch)"

**学习《Build a Large Language Model (From Scratch)》一书**

- Author: Sebastian Raschka
- BOOK: [Build a Large Language Model (From Scratch)](    https://www.manning.com/books/build-a-large-language-model-from-scratch)
- GitHub: [rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch)
- 中英文pdf版本, 可联系我获取
- 如有侵权，请联系删除

---
**目录**

* 目录
{:toc}

---
## Setup

参考
- `setup/01_optional-python-setup-preferences`
- `.setup/02_installing-python-libraries`

按照步骤配置环境:
```bash
git clone --depth 1 https://github.com/rasbt/LLMs-from-scratch.git
cd LLMs-from-scratch
conda create -n LLMs python=3.10
conda activate LLMs
conda install jupyterlab watermark
pip install -r requirements.txt
```

在这里遇到了以下问题:

<img src="https://raw.githubusercontent.com/AlanZeng423/Pics/main/MarkDown_Pics/image-20240929162323569.png" alt="image-20240929162323569" style="zoom:100%;" />

解决方案:
```bash
hash -r
```
<img src="https://raw.githubusercontent.com/AlanZeng423/Pics/main/MarkDown_Pics/image-20240929162500733.png" alt="image-20240929162500733" style="zoom:80%;" />

解释:
- `hash` 是一个 Bash 内建命令，用于查找并记住命令的位置。如果你在安装了新的软件之后，想要立即使用它，但是 Bash 仍然使用旧的命令，那么你可以使用 `hash -r` 命令来刷新 Bash 的命令缓存。

# Chapter 01
