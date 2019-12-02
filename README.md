### 使用 Sentinel 实现接口限流

### 注意：
1.本项目版本：

Spring Cloud Version| Spring Cloud Alibaba Version | Spring Boot Version
--- | --- | ---
Spring Cloud Greenwich | 2.1.1.RELEASE | 2.1.X.RELEASE

2.pom.xml中需要先引入依赖：spring-cloud-alibaba-dependencies，再引入依赖：spring-cloud-starter-alibaba-sentinel

3.先启动 Sentinel Dashboard，再访问本项目的接口，在启动的Sentinel Dashboard中就可以看到本项目alibaba-sentinel-rate-limiting这个服务以及接口调用的实时监控了

### 参考资料

参考资料 | 网址
--- | ---
Spring Cloud Alibaba基础教程：使用Sentinel实现接口限流 | http://blog.didispace.com/spring-cloud-alibaba-sentinel-1/
使用 Sentinel Dashboard 的 Docker 镜像 | https://www.cnblogs.com/cag2050/p/11970999.html
组件版本关系 | https://github.com/alibaba/spring-cloud-alibaba/wiki/%E7%89%88%E6%9C%AC%E8%AF%B4%E6%98%8E