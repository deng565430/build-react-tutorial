# 安装项目所需依赖包
首先安装一些基本的依赖包，后续会逐渐增加到全家桶的程度。
```js
//devDependencies
babel-core                       
babel-loader                     
babel-preset-latest              
babel-preset-react
babel-preset-stage-0
babel-plugin-transform-runtime
babel-plugin-transform-decorators-legacy
babel-runtime
css-loader
file-loader
less-loader
style-loader
url-loader
webpack
webpack-dev-middleware
webpack-hot-middleware
less
koa
koa-router
```
```js
//dependencies
prop-types
react
react-dom
```
运行以下命令安装开发依赖
```js
    npm i --save-dev babel-core babel-loader babel-preset-latest babel-preset-react babel-preset-stage-0 babel-plugin-transform-runtime babel-plugin-transform-decorators-legacy babel-runtime css-loader file-loader less-loader style-loader url-loader webpack webpack-dev-middleware webpack-hot-middleware less koa koa-router
```
再运行一下命令安装生产依赖
```js
    npm i --save prop-types react react-dom
```
好了，现在你的项目结构应该大致和[step0](https://github.com/sundaypig/build-react-tutorial/tree/master/step0)差不多了。  
下一步我将在[step1](https://github.com/sundaypig/build-react-tutorial/tree/master/step1)使用koa和webpack-dev-middleware搭建一个本地服务器并启动一个react页面