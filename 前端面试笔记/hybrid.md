# hybrid

* hybrid 概念
* 存在价值
* webview
* file:// 协议
* hybrid 实现流程

## hybrid 概念

![image-20230517075009542](./img/image-20230517075009542.png)

## 存在价值

![image-20230517075124595](./img/image-20230517075124595.png)

## webview

![image-20230517075152822](./img/image-20230517075152822.png)

## file 协议

* file 协议：本地文件，快
* http(s) 协议：网络加载，慢

## 实现流程

![image-20230517080331214](./img/image-20230517080331214.png)

![image-20230517080403519](./img/image-20230517080403519.png)

![image-20230517080416429](./img/image-20230517080416429.png)

## 更新上线流程

* 每次 app 打开去服务端下载最新的静态文件
* 打包上传，app 端去server端下载包，然后解压
* 版本管理，可通过时间戳

![image-20230517080539506](./img/image-20230517080539506.png)

![image-20230517080608609](./img/image-20230517080608609.png)

![image-20230517080730697](./img/image-20230517080730697.png)

![image-20230517080742498](./img/image-20230517080742498.png)

![image-20230517081009913](./img/image-20230517081009913.png)

## JS 和客户端通讯

* schema 协议
* 不能 ajax 获取，第一跨域，第二速度慢
* 客户端获取内容，然后 JS 通讯拿到内容渲染

![image-20230517081241037](./img/image-20230517081241037.png)

![image-20230517081426837](./img/image-20230517081426837.png)

![image-20230517081405444](./img/image-20230517081405444.png)

![image-20230517082404998](./img/image-20230517082404998.png)