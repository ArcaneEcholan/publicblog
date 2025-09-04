---
title: "Python 升级到3.9+"
date: "2025-09-04"
tags: ["python"]
draft: false
summary:
--

python ubuntu 20.04 desktop 自带的是3.8

```
python3 --version
Python 3.8.10
```

需要升级到更高的版本需要添加 apt 的仓库。

https://chatgpt.com/c/68ad1009-4cf0-832a-9c74-c2696fbcd16c

deadsnakes ppa

```

sudo apt update
sudo apt install -y software-properties-common

# 添加 deadsnakes PPA
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update

# 安装 Python 3.9/3.10/3.11 等
sudo apt install -y python3.9 python3.9-distutils python3.9-venv
sudo apt install -y python3.10 python3.10-distutils python3.10-venv
sudo apt install -y python3.11 python3.11-distutils python3.11-venv

```

安装完成后使用对应的python 版本命令即可。
