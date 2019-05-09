FROM registry.cn-hangzhou.aliyuncs.com/mt23/jre8-alpine-shanghai:1.0.0
MAINTAINER mt23


ADD target/xxl-job-admin-2.0.2.jar /app.jar

ENTRYPOINT ["sh","-c","java -jar /app.jar"]