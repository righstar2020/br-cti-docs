# 1.gitbook安装说明
## 1.1 安装nodejs
使用NVM安装10.24.1版本的nodejs
```shell
nvm install 10.24.1
```
```shell
nvm use 10.24.1
```
## 1.2 安装gitbook
```shell
npm install -g gitbook-cli
```
```shell
gitbook -V
```

# 2. 文档发布
生成静态html文件
```shell
gitbook build --output=/html
```

