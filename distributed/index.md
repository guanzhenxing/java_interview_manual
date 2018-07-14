# 分布式

## session 分布式处理

第一种：粘性session。粘性Session是指将用户锁定到某一个服务器上（通过NG）。

第二种：服务器session复制。

第三种：session共享机制。使用分布式缓存方案比如memcached、Redis，但是要求Memcached或Redis必须是集群。

第四种：session持久化到数据库。