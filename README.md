# dist-local-preview

dist local preview

利用http-proxy实现本地化前端项目dist目录预览


# config

```javascript
var config = {
  target: '服务器端的地址',
  port: 3001, // 本地server 的port
  host: '0.0.0.0', // 本地server 的host
  dir: '../dist', // 监听dist 目录
  prefix: '/api', // 服务器端的api 接口 前缀
  debug: true // 是否开启本地日志。
};
```
