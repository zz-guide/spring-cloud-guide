#1.服务注册发现：Eureka
- 地址：http://localhost:8666/

#2.maven忽略ssl
-Dmaven.wagon.http.ssl.insecure=true -Dmaven.wagon.http.ssl.allowall=true -Dmaven.wagon.http.ssl.ignore.validity.dates=true


#3.熔断和负载均衡都是配置在调用方的，或者可以配置一个网关服务自带负载均衡

#4.微服务结构

客户端

服务端

网关

负载均衡器

熔断器

Spring Cloud Bus+Spring CLoud Config 实现动态配置刷新