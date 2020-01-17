分布式：不同的多台服务器上面部署不同的服务模块（工程），他们之间通过Rac/Rmi之间通信和调用，对外提供服务和组内协作；

集群：不同的多台服务器上面部署相同的服务模块，通过分布式调度软件进行统一的调度，对外提供服务和组内协作；

## Redis介绍

```python

Redis:REmote DIctionary Server(远程字典服务)，是完全开源免费的，C语言编写的，遵守BSD协议，是一个高性能的（key/value）分布式内存数据库，基于内存运行，也被人们称为数据结构服务器
    
# Redis特点：
Redis支持数据的持久化，可以将内存中的数据保持在磁盘中，，重启的时候可以再次加载进行使用；
Redis不仅仅支持简单的key=value类型的数据，同时还提供list，set，zset,hash等数据结构的存储；
Redis支持数据的备份，即master-slave模式的数据备份；
下载地址：https://redis.io/download
```

