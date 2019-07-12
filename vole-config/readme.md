# 服务管理

## 问题

- 微服务的配置中心
  > search-locations: classpath:/resposity
  > 

## 步骤

- startup
  ```
  cd ~/Desktop/Git.d/vole/vole-config
  mvn package
  
  cd target
  java -jar vole-config-1.0.0-SNAPSHOT.jar
  java -jar vole-config-1.0.0-SNAPSHOT.jar --spring.profiles.active=node1
  ```
