# docker-cloud说明
容器云的基本镜像，基于标准镜像centos:7生成
加入常用网络工具以及相关开发环境

## 主要包含：
*  基本网络组件 net-tools bind-utils wget telnet nc tcpdump
*  守护进程 supervisor ctl
*  openssh 7.4
*  openjdk 1.8.0.161
*  tomcat 8.5

## 使用
    docker run -d cloud:1.0

