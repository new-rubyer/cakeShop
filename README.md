# 蛋糕街
nodejs + express + mongodb 完成的一个小型电商网站

#安装部署
1. 安装nodejs、mongoDB
2. 启动mongoDB
3. $npm install 安装依赖包
4. npm run dev 在开发环境中运行  npm run dist 在生产环境中运行
5. visit http://localhost:7777 dev的端口是7777 dist端口是8888
6. done！

#目录结构
<pre>
- controllers 存放控制器的
- models 存放model，一些表的结构
- router 存放路由文件
- static 存在静态资源
- views 存放页面html文件
- app.js 入口文件
- .bowerrc 指定bower安装的目录
- .editorconfig 配置一些编程习惯配置
- gulpfile.js gulp自动化配置文件
- index.js 总的入口文件，npm run时调用
- package.json npm的配置文件
</pre>

fock后，本地试搭过程如下：
wap网站，电脑访问格式不全。初体验很好的。
node npm mongdb环境配置基本没什么问题，在npm install 之后是缺少了cross-env 和 nodemon
命令分别是：
npm i cross-env --save-dev
npm install -g nodemon
还有一点我是关掉防火墙访问的，继续看下，谢谢。。
