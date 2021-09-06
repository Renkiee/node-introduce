# node
nodejs,是js在服务端的一个运行环境，封装了文件以及一些底层系统库，让js可以和底层系统进行交互。可以类比浏览器环境（window，document-->html），遵循commonjs模块规范.
通常被用来写爬虫工具，中间层，cli工具，也可以直接操作数据库，作为服务端开发语言。

1.1 底层依赖
v8 解析js代码  
libuv 事件驱动库，处理event loop


1.2 全局对象
global process settimeout  
tip: require module module.exports __dirname __filename 不是全局对象，因为是commonjs解析模块时注入进去的，所以也可以全局使用

1.3 内置模块
buffer 二进制数据内存缓冲区
event
fs
path
Stream

