# scss学习笔记

## sass是什么?
Sass(英文全称: Syntactically Awesome Stylesheets) 
是由一个最初Hampton Catlin设计并由Natelie Weizenbaumka开发的类css语言。  
发行时间: 2007年
稳定版本: 2016年3月28日

Sass 十分简洁，语法中几乎不含括号。
后来前端工程师表示不含括号看不懂，于是 Sass 的开发者又提供了 Scss，含括号。
弱弱的前端工程师终于表示能看懂了。

Sass的官方解释器是开源的并且用Ruby语言写成，但是也有用PHP、C语言、Java等实现的版本（C语言版本叫做llibSass，Java语言版本叫做JSass）。

SassScript提供以下功能：变量、嵌套、混入（Mixin）、选择器继承等。

## 环境配置 - parcel

1: 安装http-server
npm install -g http-server

2: 安装parcel
npm install -D parcel

3: 启动parcel
npx parcel $filename

parcel会自动加载scss所需的构建文件
