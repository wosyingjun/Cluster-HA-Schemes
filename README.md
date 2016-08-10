#集群高可用架构整理（不断更新中）
>在大型系统或是对稳定性要求较高的项目中，集群高可用架构是必不可少的，这里整理一些平时用到过的集群/高可用技术，不断更新中。。。

####二种最基本的集群模型：

-  **M-S 型集群:** M-S 型的集群一般用于高可用架构，主节点挂掉时从节点顶上，一般不具有分流（负载均衡）的作用。  
-  **M-M 型集群:** M-M 型的集群一般用于分流（负载均衡），部分 M-M 型集群会包含 M-S 型的主从功能（像 Redis Cluster），分流的同时达到高可用的作用。  
  

####传送门：  
- **[Redis Sentinel 主从高可用方案（附Jedis Sentinel教程）](http://wosyingjun.iteye.com/blog/2289593)**   
- **[Redis Cluster 集群主从方案（附Jedis Cluster教程）](http://wosyingjun.iteye.com/blog/2289220)**  
- **[ZooKeeper 高可用集群的安装及配置](http://wosyingjun.iteye.com/blog/2312960)**  
- **[Tomcat 集群（Redis 共享 Session）](https://github.com/wosyingjun/beauty_ssm_cluster)**  
- **[基于keepalived 的 Nginx 高可用集群方案](http://wosyingjun.iteye.com/blog/2313147)**  
- **[Kafka 集群的部署与测试](http://wosyingjun.iteye.com/blog/2316508)**
- **[ActiveMQ 高可用集群方案](http://wosyingjun.iteye.com/blog/2314683)**  
- **Flume 集群负载均衡（待完善）**
- **Storm+Esper 分布式集群（待完善）** 



####相关项目：  
- **[推荐几个自己写的范例项目](http://wosyingjun.iteye.com/blog/2312553)** 
- **[Leek—简易版实时智能选股平台](https://github.com/wosyingjun/Leek)** 
