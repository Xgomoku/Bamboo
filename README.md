# Bamboo
It is a complete information collection framework prototype, which can be used directly, or can be added or enhanced on the existing framework.


## 管理后台(CMS)
支持，种子管理，解析存储规则管理，查看资讯。

## 调度器
基于redis的有序集合设计的一个延迟任务队列。
精度1s，支持优先级队列，并发控制。

## 下载器
基于开源go框架colly设计的高并发下载器。
日吞吐700W+，自动切换代理，支持深度/广度扩展控制。


## 解析存储
支持xpath/jsonpath抽取规则，可抽列表或单页，自动入库。
