# ms-demo
micro service demo

1. 两个以上的微服务
2. 使用Restful和MQ进行通信
3. 实现客户端负载均衡
4. 有服务注册和发现中心
5. 使用config sever配置config
6. 有熔断机制
7. 使用cache， redis
8. 数据要保存到 DB.
9. 至少要有一个UI
 按照以上要求搭建一个基本的微服务框架
 
1. 两个以上的微服务
2. 使用Restful和MQ进行通信
3. 实现客户端负载均衡
4. 有服务注册和发现中心
    Eureka Server Netflix
5. 使用config sever配置config
6. 有熔断机制
7. 使用cache， redis
8. 数据要保存到 DB.
9. 至少要有一个UI
按照以上要求搭建一个基本的微服务框架
 
spring boot cloud  
~~gradle + ali 镜像~~
FAQ frequently answered question 
** how to start spring boot project? user spring initializer
** gradlew 要不要提交? 要
** gradle build 太慢了? gradle-wrapper.properties 访问了墙外; 
    C:\Users\xxx\.gradle\wrapper\dists\gradle-6.5.1-bin\1m5048aptkfynhbvolwgr4ej9\ 目录下放自己下载的 gradle-6.5.1-bin.zip
** gradle plugin 下载不到? 配置settings.gradle, 用ali 镜像 
** 每个微服务都要各自一个git 仓库嘛? 貌似是的, 为了独立部署, 组织架构blah blah; 折衷, 为了方便在一个IDE里搞, 不分了
  
