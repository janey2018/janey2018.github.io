---
title: Ayer中文说明
---
Ayer 在马来语中是“水”的意思，在西班牙语中是“昨天”的意思。

## 安装

### 方法一：

``` bash
npm i hexo-theme-ayer -S
```

### 主题内容：根目录 _config.ayer.yml


-----


### 方法二：

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
