# 使用JDK8环境作为基础镜像
FROM java:8

# 拷贝JRA包
COPY build/libs/alice-0.0.1-SNAPSHOT.jar alice.jar

# 容器启动时运行
ENTRYPOINT ["java","-jar","/alice.jar"]

#暴露端口
EXPOSE 8080