# Bamboo
这是一套完整的资讯收录框架原型，可直接使用，或在现有架构上做功能添加、增强。


### 管理后台(CMS)
支持，种子管理，解析存储规则管理，查看资讯。

### 调度器
基于redis的有序集合设计的一个延迟任务队列。
精度1s，支持优先级队列，并发控制。

### 下载器
基于开源go框架colly设计的高并发分布式下载器。
单核日吞吐700W+，自动切换代理，支持深度/广度扩展控制。

### 解析存储
支持xpath/jsonpath抽取规则，可抽列表或单页，自动入库。

### 流程图
![image](https://github.com/Xgomoku/Bamboo/blob/main/images/img.svg)

### 基本功能
## 添加数据源
![image](https://github.com/Xgomoku/Bamboo/blob/main/images/seeds.gif)

## 添加解析规则
![image](https://github.com/Xgomoku/Bamboo/blob/main/images/rule.gif)

## 查看采集结果
![image](https://github.com/Xgomoku/Bamboo/blob/main/images/news.gif)
