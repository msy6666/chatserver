# chatserver
工作在Nginx tcp负载均衡环境中的集群聊天服务器和客户端
基于muduo网络库做服务器编程
基于json序列化反序列化交换数据
基于MYSQL设计用户表、好友表、群组表、群组成员表、离线消息表
基于发布-订阅的redis消息队列实现跨服务器通信
通过cmake实现一键编译

#编译流程
cd build
rm -rf *
cmake ..
make
或直接采用一键编译脚本autobuild.sh
