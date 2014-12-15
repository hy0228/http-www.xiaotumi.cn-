http-www.xiaotumi.cn-
=====================

使用 Node.js、Express、AngularJS 和 MongoDB 构建一个实时问卷调查应用程序



我决定快速构建一个用于此目的的问卷调查应用程序。我想要一个简单的架构，不需要太多不同的语言和框架。因此，我决定对所有一切都使用 JavaScript — 对服务器端使用 Node.js 和 Express，对数据库使用 MongoDB，对前端用户界面使用 AngularJS。

数据库
MongoDB的链接文件目录polls\config\environments\all.js

module.exports = {
    name:'all',
    "mongoUrl": "mongodb://localhost/polls"
};

开始

$ npm install

$ node app.js

浏览器打开：http://localhost:8080

盼喜欢。参考地址 http://www.ibm.com/developerworks/cn/web/wa-nodejs-polling-app/index.html
