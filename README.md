# 脚手架
## npm link
npm link是一种把包链接到包文件夹的方式，即：可以在不发布npm模块的情况下，调试该模块，并且修改模块后会实时生效，不需要通过npm install进行安装。


## 调试阶段时
为了保证 js-plugin-cli 指令可用，我们需要在项目下执行 npm link（不需要指令时用 npm unlink 断开）。

# 参考资料
- [Node.js 如何处理 ES6 模块](https://www.ruanyifeng.com/blog/2020/08/how-nodejs-use-es6-module.html)

