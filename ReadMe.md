# Typescript 项目 

## 创建项目
1. 初始化项目
    `npm init` 创建 package.json 

2. 创建目录结构
    `md src build typings`
    + src 为主要项目入口文件夹
      - src/api 项目api模块
      - src/assets  项目静态文件模块
      - src/config  项目配置模块
      - src/plugins 插件
      - src/tools   项目工具模块
      - src/utils   项目公共模块
      - src/index.ts 项目入口文件
    + build 生成文件
    + typings ts自动识别模块文件
3. typescript 相关校验文件
    `npm install typescript tslint -g`

4. webpack 安装
    `npm install webpack webpack-cli webpack-dev-server -D`
    build 中创建 webpack.config.js 文件进行 webpack 配置
5. typscript 格式检查插件
    `npm install typescript -D`
    `npm install ts-loader -D`
6. 环境配置插件
    `npm install cross-env -D`
7. `npm install clean-webpack-plugin -D` 文件清理不必要文件插件
   `npm install  html-webpack-plugin -D` html模板插件

## TypeScript 语法

3. 重要类型 对应文件 example/ advanced-type-2 内容
   `keyof` 查询类型的属性 只能映射

9. 装饰器
   1.  装饰器作用在函数上，是从上往下获取装饰器方法，从下往上一次调用
