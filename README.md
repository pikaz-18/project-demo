<!--
 * @Author: zouzheng
 * @Date: 2020-06-08 17:09:00
 * @LastEditors: zouzheng
 * @LastEditTime: 2020-06-09 10:34:41
 * @Description: 这是XXX组件（页面）
--> 
## 多项目共用组件demo-项目

### 引入组件

写入package.json依赖中，并执行npm install即可

```js
"dependencies": {
    "compoment-demo": "git+https://github.com/pikaz-18/compoment-demo.git"
  }
```

之后更新时，只需执行npm install compoment-demo即可
也可以将此命令写入打包命令中，以确保项目使用的组件为最新
```js
"scripts": {
    "build": "npm install compoment-demo && vue-cli-service build"
  }
```