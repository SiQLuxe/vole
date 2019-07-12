# 服务管理

## 问题


## 步骤

- startup
  ```
  cd ~/Desktop/Git.d/vole/vole-modules/vole-ssoclient
  mvn package
  
  cd target
  java -jar vole-eureka-1.0.0-SNAPSHOT.jar
  java -jar vole-eureka-1.0.0-SNAPSHOT.jar --spring.profiles.active=node1
  ```
