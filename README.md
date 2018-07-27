# mvv-c
让数据库和vue-cli结合到一个项目结构中去

//没研究出来啊。。。。

把mongo+koa一整套复制过来到一个新的文件夹下。

然后在build文件下的webpack.dev.conf.js配置文件 引用

const main = require('../servers/index.js'); //引用servers文件夹下的index文件即可

虽然有想要的效果，但是感觉有问题。。。。。