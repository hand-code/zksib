# zksib
转客平台消息系统,zk message 's system

整个系统主要包括mq,message producer,message agent,token center server

project roadmap
token center server:
1.message protocol
2.async to dbstore
3.manage protocol 
4.manage webui interface
5.get token from weixin's gateway

message agent:
1.send weixin message to weixin's gateway

message producer:
1.produce many template messages
2.send message to mq server(for example:beanstalkd)

