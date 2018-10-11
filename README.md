# MicroserviceMall
SpringBoot+Dubbo+Docker+Jenkins，仿<a href="https://github.com/bz51/SpringBoot-Dubbo-Docker-Jenkins">https://github.com/bz51/SpringBoot-Dubbo-Docker-Jenkins</a>
### 4.2获取Tomcat镜像：docker pull chaimm/tomcat:1.1
### 4.3创建Tomcat容器：
  user:docker run --name mall-user-1 -p 8082:8080 -v /usr/web/mall-log:/opt/tomcat/mall-log chaimm/tomcat:1.1
  product:docker run --name mall-product-1 -p 8083:8080 -v /usr/web/mall-log:/opt/tomcat/mall-log chaimm/tomcat:1.1
  order:docker run --name mall-order-1 -p 8084:8080 -v /usr/web/mall-log:/opt/tomcat/mall-log chaimm/tomcat:1.1
  analysis:docker run --name mall-analysis-1 -p 8085:8080 -v /usr/web/mall-log:/opt/tomcat/mall-log chaimm/tomcat:1.1
  controller:docker run --name mall-controller-1 -p 8086:8080 -v /usr/web/mall-log:/opt/tomcat/mall-log chaimm/tomcat:1.1
  redis:docker run --name mall-redis-1 -p 8087:8080 -v /usr/web/mall-log:/opt/tomcat/mall-log chaimm/tomcat:1.1
