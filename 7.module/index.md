#模块
##JS先天不足
- JS没有原生的模块系统，不支持封闭的作用域和依赖管理
- 没有标准库，不支持文件系统和流
- 没有包管理系统，不能支持自动加载和安装依赖

##common.js
以模块划分所有的功能。每一个JS都是一个模块。
实现了require方法。
npm 基于commonjs实现了自动加载安装依赖

##优点
- 增加了内聚性
- 有助分工
- 有助重构
- 提交代码质量和开发效率
