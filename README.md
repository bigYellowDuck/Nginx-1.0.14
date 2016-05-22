# Nginx-1.0.14

##学习过程
这份Nginx-1.0.14版的源码是我个人学习Nginx时注释的，参考书籍是陶辉写的《深入理解Nginx 模块开发与架构分析》
主要学习和注释了Nginx启动，事件模块和HTTP框架的初始化部分，先从src/core/nginx.c入手了解Nginx启动和运行的
大概流程，再去看ngx_event_module，ngx_event_core_modole，ngx_epoll_module模块，然后看ngx_http_module模块，
最后了解Nginx分阶段处理HTTP请求。分别对应于《深入理解Nginx 模块开发与架构分析》的第8~11章节的内容。
    
###个人总结
  个人关于Nginx启动过程，事件模块，HTTP模块的总结在summary文件夹中。

	

	
	
