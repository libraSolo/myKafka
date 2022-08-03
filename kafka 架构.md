# kafka 架构

 ## 整体来看

kafka 是一个消息队列 MQ

## kafka 集群

为了解决三高(高可用  高性能  高并发)问题, 需要实现 kafka 集群架构

## kafka 消息主题

消息分类, 保存在 kafka 服务器中的数据按照主题(Topic) 进行了逻辑分类

## kafka 分区

kafka 可以将主题划分为多个分区(partition)

## kafka 副本

针对服务器宕机,数据不可用问题