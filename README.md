# simple-nodejs-server
最简单朴素的 Node.js 服务器，`server.js` 代码揭示了服务器路由的本质。

## 启动应用

`node server.js 8888`
在浏览器访问`localhost:8888/<URL路径>`

## 添加路由

1. 编辑 server.js 文件，添加 if else
2. 重新运行 node server.js 8888

## 后台启动应用

```
touch log
node server.js 8888 >log log 2>&1 &
```
