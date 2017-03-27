# reactsutdy


## 包管理器npm 

### 安装包：###


1. 全局安装 `npm install 包 -g`
2. 本地安装 `npm install 包 [--save /--save-dev]`

### 使用package.json ###

1. 手动创建
1. npm init

## 安装webpack ##

### 全局安装？本地安装 ###

	npm install webpack -g
	npm install webpack --save-dev

指定安装版本

	npm install webpack@1.12.14 -g

### webpack配置文件
webpack.config.js

### webpack使用loader ###
- 理解loader
- style-loader
- css-loader


### webpack使用plugin ###
HtmlWebpackPlugin 等插件的安装与使用

### webpack实时构建 ###
    webpack -w
    webpack-dev-server

## 执行hello world 编译 ##

	webpack ./index.js bundle.js

## 使用react 与传html开发的比较 ##
- 局部更新与全量更新
- 全量更新的缺陷
- 引入react

## JSX语法 ##
### jsx来历
Facebook 的内部项目,然后开源。
### jsx语法
	React.createElement()

### jsx编译
jsx在网页上不能直接浏览，需要进行编译后才能浏览

- 网页编译 JSXTransformer
- Babel编译

### 安装配置Babel

	npm install babel-core babel-loader --save-dev
	npm install babel-preset-es2015 babel-preset-react --save-dev
### 配置Babel .babelrc
	{
		"presets":["es2015","react"]
	}

## React 三大特征
- JSX
- 组件(属性,状态)
- Virtual DOM

