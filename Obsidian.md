
# Code相关

## mac上

```python
# 安装brew
https://brew.idayer.com/

# 安装git
brew install git

# 生成密钥 到github配置：
https://www.bilibili.com/video/BV1xN411w7iV/

git config --global user.name "acse-119"
git config --global user.email "mongotianxuhe@gmail.com"

ssh-keygen -t rsa -C "mongotianxuhe@gmail.com"

cat /Users/temp/.ssh/id_rsa.pub
ios:
cat /root/.ssh/id_rsa.pub

git clone git@github.com:acse-th119/obsidian-notes-txdemo.git

# 设置iSH
https://zhuanlan.zhihu.com/p/565028534

ssh -T git@github.com

git clone https://github.com/acse-th119/obsidian-notes-txdemo.git
```

## ios上

下载iSH App
在里面运行
```bash
apk update
apk add git
apk add vim
apk add openssh
apk add openrc
apk add bash
```