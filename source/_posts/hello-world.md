---
title: Ayer中文说明
categories: hexo
tags: ["hexo"]
top: 1
---

Ayer 在马来语中是“水”的意思，在西班牙语中是“昨天”的意思。

<!--more-->

## 安装

### 方法一：
> 如果是新安装本主题，安装完成后会在根目录生成一个`_config.ayer.yml`文件，直接编辑`_config.ayer.yml`文件进行配置即可。
> 如果是主题升级，建议先把配置内容做备份，然后用`npm uninstall hexo-theme-ayer -S`先卸载主题，再执行下面命令重新安装。


``` bash
npm i hexo-theme-ayer -S
```

### 主题内容：根目录 _config.ayer.yml


-----


### 方法二：
> hexo < 5.0

``` bash
git clone https://github.com/Shen-Yu/hexo-theme-ayer.git themes/ayer
```


### 主题配置：根目录 _config.yml

``` bash
theme: ayer
```

----

### 新建侧边：分类

``` bash
hexo new page categories
```
然后将以下复制到 /source/categories/index.md 文件

``` bash
title: categories
type: "categories"
layout: "categories"
```

----
## 问题
http://localhost:4000/search.xml 404 (Not Found)
