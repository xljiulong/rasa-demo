# 系统配置
## 环境创建
```
conda create -n py38 python=3.8
```
## 激活环境
```
conda activate py38
```

## 设置源
```
export PIP_INDEX_URL=https://mirrors.aliyun.com/pypi/simple/
or 
export PIP_INDEX_URL=https://pypi.tuna.tsinghua.edu.cn/simple  更快
```

## 代理设置
```
export HTTP_PROXY=http://192.168.200.26:58591
export HTTPS_PROXY=http://192.168.200.26:58591
```
## 取消代理
```

```
# rasa安装
1. spacy~=2.2.4 conda 安装
2. 其余 pip安装
