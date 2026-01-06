FROM registry.cn-hangzhou.aliyuncs.com/jeecgdocker/mysql:8.0.19

MAINTAINER jeecgos@163.com

ENV TZ=Asia/Shanghai

RUN ln -sf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

COPY ./jeecgai-mysql-5.7.sql /docker-entrypoint-initdb.d