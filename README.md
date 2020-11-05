# redis_cluster-docker-compose
编排redis cluster集群
注意事项：docker网络必须使用host，否则集群加入失败
https://blog.csdn.net/linux_yyp/article/details/108364285

>
使用的docker镜像
>
docker pull redis:4.0.10
>
docker pull redis:5.0.9
>
docker pull redis:6.0.7
>
docker pull zvelo/redis-trib
