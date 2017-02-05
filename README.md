#Simple Http Server
##Introduce:
再次造轮子的原因是为了实现2017年的几个小目标

1. 实现简单的 HTTP服务器（支持 GET/POST/CGI），然后用浏览器访问，里面有个CGI留言板。

2. 实现一个简版 REDIS，或者给 Redis加10条命令，或者把后面存储引擎换成 unqlite，再开源

3. 给 apache实现一个 module，可以支持 lua来写服务。

4. 给 nginx写一个 python模块，可以python来写服务。

5. 用 C/C++/go写个代理翻墙软件，跑在你的海外租的 vps上。

6. 实现一套简单的 TCP RPC框架，并再基础上做一个简单聊天。

7. 阅读 Linux代码，应用层实现一个 Linux的定时器。

这是第1个目标

这个HttpServer的目的只是为了练手，尽量不引入任何第三方的依赖，仅靠标准C及C++代码来实现
不知道什么时候能完成=。=
