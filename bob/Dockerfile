# 使用JDK8环境作为基础镜像
FROM java:8

# 拷贝JRA包
COPY build/libs/bob-0.0.1-SNAPSHOT.jar bob.jar

# 容器启动时运行
ENTRYPOINT ["java","-jar","/bob.jar"]

#暴露端口
EXPOSE 8081