
127.0.0.1:5000 可以获取到localIP

Accept-Ranges: bytes
Connection: keep-alive
Content-Disposition: inline; filename="index.html"
Content-Length: 6886
Content-Type: text/html; charset=utf-8
Date: Tue, 24 Mar 2020 05:54:12 GMT
Last-Modified: Tue, 24 Mar 2020 05:52:28 GMT

localhost:5000 不可以获取到localIP

Accept-Ranges: bytes
Connection: keep-alive
Content-Disposition: inline; filename="index.html"
Content-Length: 6886
Content-Type: text/html; charset=utf-8
Date: Tue, 24 Mar 2020 05:55:04 GMT
Last-Modified: Tue, 24 Mar 2020 05:52:28 GMT

http://10.224.36.179:5000 不可以获取到localIP

Accept-Ranges: bytes
Connection: keep-alive
Content-Disposition: inline; filename="index.html"
Content-Length: 6886
Content-Type: text/html; charset=utf-8
Date: Tue, 24 Mar 2020 05:57:38 GMT
Last-Modified: Tue, 24 Mar 2020 05:52:28 GMT


localhot(local)是不经网卡传输！这点很重要，它不受网络防火墙和网卡相关的的限制。

127.0.0.1是通过网卡传输，依赖网卡，并受到网络防火墙和网卡相关的限制。

本机IP 也是通过网卡传输的，依赖网卡，并受到网络防火墙和网卡相关的限制。 

但是本机IP与127.0.0.1的区别是： 127.0.0.1 只能通过本机访问，而本机IP通过本机访问也能通过外部访问  