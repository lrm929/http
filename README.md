# http
#最简单的方式启动 一个http 服务用于跑静态文件 或者下载文件 最合适不过 关键不需要安装任何软件 只依赖python

#A 使用方法 

#1  下载 lrm_http 启动脚本到 /etc/init.d/  目录下 

#2  给执行权限 chmod +x  /etc/init.d/lrm_http

#3  /etc/init.d/lrm_http start  #启动

#4  /etc/init.d/lrm_http  stop  #停止

#5  /etc/init.d/lrm_http  restart #重启

#就是这么简单直接一个启动脚本搞定一个http 服务


#B 修改配置说明

#config  如果想改变端口跟根目录直接修改即可 切记先停止服务在进行修改

#default port is 20000 

#port=20000

#default  root is /tmp

#dir_root=/tmp

#最后给一个阿里云优惠券福利给大家  点击打开即可领取 https://promotion.aliyun.com/ntms/yunparter/invite.html?userCode=myidpz5r&utm_source=myidpz5r
###test
