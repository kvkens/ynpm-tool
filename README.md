## 概述

基于ynpm改版而来.更名为tnpm

使用淘宝的镜像源来下载NPM包，不会更改默认的全局registry。仅此而已。

为什么不用cnpm?

因为cnpm会按照它的那种包名`_版本@包名`并且链接到一个快捷方式的文件夹来的，并且之后再用npm是无法安装成功的。

关于镜像和命令行工具说明如下：




## 安装

```
npm install tnpm-tool -g
```



## 使用

```
# 安装(install相关命令均支持)
tnpm install xxx --option

# 帮助
tnpm 或 tnpm -h 或 tnpm --help

# 版本
tnpm -v 或 tnpm --version
```
