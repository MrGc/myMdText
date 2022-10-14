# Python学习

### 抓包工具

`Fiddler`用于抓取http数据包

### Http头

* Host:

  指定被请求的资源的Internet主机和端口号；

* Connection：keep-alive

​		HTTP 长链接(持久连接),客户端和服务端简历一次连接之后，可以在这条链接上进行多次请求/响应操作。持久连接，可以设置过期时间(Keep-Alive:timeout=60)， 也可以不设置。

* Accept:\*/\*

​		表示浏览器能接受任何类型的文件。

* X-Requested-With:XMLHttpRequest

​		表明这是一次Ajax请求(异步)，非传统请求(同步)

* User_Agent:Mozilla/5.0(Windows NT 6.1:WOW64)

​		用户代理。告知服务器请求方所使用的操作系统及版本，CPU类型，浏览器及版本，浏览器渲染引擎，浏览器语言，浏览器插件等。

* Accept-Encoding:gzip,deflate

​		设置从网站中接受的返回数据是否进行gzip压缩。

* Cookie:BDUSS=xxx

​		储存在本地的缓存数据，随HTTP请求一起发送，用来给服务端验证，比如是否已经登录。



### HTTP接口工具

(1) 接口手动测试工具：`Fiddler` `Postman` `Wireshak`

(2)接口自动化测试工具：`JMeter` `soapUI`

(3)接口性能测试工具：`LoadRunner` `JMeter` `soapUI` 



---

### python2.7安装M2Crypto

```sh
pip install wheel
pip install cryptography
pip install M2CryptoWin64
```

