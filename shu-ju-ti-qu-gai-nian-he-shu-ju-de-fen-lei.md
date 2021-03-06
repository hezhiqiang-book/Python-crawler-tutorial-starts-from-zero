# 数据提取概念和数据的分类

* [数据提取](shu-ju-ti-qu-gai-nian-he-shu-ju-de-fen-lei.md#数据提取)
  * [介绍](shu-ju-ti-qu-gai-nian-he-shu-ju-de-fen-lei.md#介绍)
  * [概要](shu-ju-ti-qu-gai-nian-he-shu-ju-de-fen-lei.md#概要)
  * [数据提取概念和数据的分类](shu-ju-ti-qu-gai-nian-he-shu-ju-de-fen-lei.md#数据提取概念和数据的分类)
    * [什么是数据提取](shu-ju-ti-qu-gai-nian-he-shu-ju-de-fen-lei.md#什么是数据提取)
    * [数据的种类](shu-ju-ti-qu-gai-nian-he-shu-ju-de-fen-lei.md#数据的种类)
      * [构化数据](shu-ju-ti-qu-gai-nian-he-shu-ju-de-fen-lei.md#构化数据)
      * [非结构化数据](shu-ju-ti-qu-gai-nian-he-shu-ju-de-fen-lei.md#非结构化数据)
    * [总结](shu-ju-ti-qu-gai-nian-he-shu-ju-de-fen-lei.md#总结)

## 数据提取

### 介绍

> 用网络获取的数据中提取出想要的数据。

### 概要

* 数据提取概念和数据的分类
* 使用 `json` 模块提取数据
* 使用正则表达式提取数据
* 使用 `xpath` 提取数据
* 使用 `beautifulsoup` 提取数据
* `json`、`csv` 数据转换

### 数据提取概念和数据的分类

#### 什么是数据提取

> 简单的来说，数据提取就是从响应中获取我们想要的数据的过程

#### 数据的种类

**构化数据**

* **数据类型**
* json 格式数据

  ```javascript
  {
  "name":"hello",
  "age":18,
  "parents":{
    "mother":"妈妈",
    "father":"爸爸"
  }
  }
  ```

* xml 格式数据

  ```markup
  <bookstore>
  <book category="COOKING">
    <title lang="en">Everyday Italian</title> 
    <author>Giada De Laurentiis</author> 
    <year>2005</year> 
    <price>30.00</price> 
  </book>
  <book category="CHILDREN">
    <title lang="en">Harry Potter</title> 
    <author>J K. Rowling</author> 
    <year>2005</year> 
    <price>29.99</price> 
  </book>
  <book category="WEB">
    <title lang="en">Learning XML</title> 
    <author>Erik T. Ray</author> 
    <year>2003</year> 
    <price>39.95</price> 
  </book>
  </bookstore>
  ```

* 处理方式

  > 通过 json 模块等直接转成 Python 数据类型

**非结构化数据**

* 数据类型
  * html 格式数据
  * word 格式数据
  * 等
* **处理方式**

  > 通过 `正则表达式` 、 `xpath` 、`beautifulsoup` 等模块提取数据

#### 总结

* 数据提取 从网络获取数据中提取想要的数据
* 数据的种类
  * 结构化数据
  * json
  * xml
* 非结构化数据
  * html
  * word

