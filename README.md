# zksib
转客平台消息系统,zk message 's system

整个系统主要包括mq,message producer,message agent,token center server

project roadmap
---------------

token center server
----------------------

>  - message protocol    
>  - async to dbstore    
>  - manage protocol     
>  - manage webui interface    
>  - get token from weixin's gateway


message agent:
----------------

>  - send weixin message to weixin's gateway

message producer:
--------------------
>  - produce many template messages
>  - send message to mq server(for example:beanstalkd)![上一张图吧][1]


----------


  [1]: http://hd.chenxf.org/static/images/fzs.png
