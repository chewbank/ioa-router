# ioa-router

集成 middleware、controller、router 加载器的 ioa 路由基础依赖

### Install

```
npm i ioa-router
```



## 下一版优化策略

使用{name}格式替代:name

预判断{name}是部分匹配还是完全匹配，将部分匹配转为正则表达式即可，例如：

/:name/:id

/{name}/{id}

/{name}.json

'admin'.match(/value/)

'admin'.match(value)