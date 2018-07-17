## 一个简单的pwa页面

### 打开node服务
```js
npm start
```

### 查看页面
访问下面网址，注意因安全限制，只能打开localhost或者https的网站
```
http://localhost:8080/
```

这个时候，我们[**第一个pwa的项目**](https://github.com/zhyjor/first-pwa-page)也就出来了,就是一个页面。我们启动node服务，打开页面，可以将其添加到桌面上。而且这个时候，当我们停掉node服务后，刷新页面，页面就是通过缓存打开的。这个时候假如用chrome的`ctrl+F5`刷新页面，就会发现页面离线了，这个时候因为我们已经将缓存删除了。

![](http://oankigr4l.bkt.clouddn.com/201807171559_426.png)