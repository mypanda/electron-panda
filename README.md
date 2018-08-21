# electron-panda

### 入门
* `electron`全局是`global`,虽然看见浏览器的模样，但是环境属于`node`的范围而非`chrome`,所以要使用`node`的`api`
```
index.html
<p>document.write(process.versions.node) Node.js</p>
<p>document.write(process.versions.chrome) Chromium</p>
<p>document.write(process.versions.electron) electron</p>
```
### refer
* 关于打包，启动，开发的配置参数[LINK](https://blog.csdn.net/a1170201028/article/details/59108126)
* 大佬的electron[LINK](https://newsn.net/category/electron/)