# 真实面试题
## 基础
### HTML
- [HTML5新增了哪些内容或API](https://github.com/seabornlee/frontend-interview/blob/master/basics/html/HTML5%E6%96%B0%E5%A2%9E%E4%BA%86%E5%93%AA%E4%BA%9B%E5%86%85%E5%AE%B9%E6%88%96API.md)
- [input 和 textarea 的区别](https://github.com/seabornlee/frontend-interview/blob/master/basics/html/input%20%E5%92%8C%20textarea%20%E7%9A%84%E5%8C%BA%E5%88%AB.md)
- [用一个div模拟textarea的实现](https://github.com/seabornlee/frontend-interview/blob/master/basics/html/%E7%94%A8%E4%B8%80%E4%B8%AAdiv%E6%A8%A1%E6%8B%9Ftextarea%E7%9A%84%E5%AE%9E%E7%8E%B0.md)
- [如何忽略页面中的电话号码](https://github.com/seabornlee/frontend-interview/blob/master/basics/html/%E5%A6%82%E4%BD%95%E5%BF%BD%E7%95%A5%E9%A1%B5%E9%9D%A2%E4%B8%AD%E7%9A%84%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81.md)
### CSS
- 布局
	- 右边宽度固定，左边自适应
	- 水平垂直居中
	- 四种定位的区别
	- Flex布局
	- 移动端适配怎么做
	- 左右布局：左边定宽、右边自适应，不少于3种方法
	- 水平居中有哪些实现方式
- 动画
	- 使用css实现一个持续的动画效果
- 特性
	- CSS3 新特性
	- BFC、IFC
	- 对栅格的理解
	- 1像素边框问题
	- 图片懒加载
	- 实现页面加载进度条
### JavaScript
- 动画
	- 使用js实现一个持续的动画效果
	- 什么情况会触发重排和重绘？
- 语法
	- 为什么 var 可以重复声明
- 特性
	- 封装一个函数，参数是定时器的时间，.then执行回调函数
	- 实现 extend 函数
- OO
	- 一个关于 this 指向的问题
	- 怎么判断两个对象相等？
- 数据结构
	- 一行代码实现数组去重？
	- Set 和 Map 数据结构
	- WeakMap 和 Map 的区别?
	- 说一下深拷贝的实现原理
	- 找出两个链表第一次的交点
- 事件
	- 使用addEventListener点击li弹出内容，并且动态添加li之后有效
	- 拖拽功能
- 异步
	- Promise 的实现原理
	- 进一步会问 async、await 是否使用过
- ES6
	- 箭头函数特性
	- CommonJS 中的 require/exports 和 ES6 中的 import/export 区别？
	- let与var的区别
- 手写 parseInt 的实现
- 依赖
	- require.js的实现原理

### 浏览器
- 浏览器缓存
- 页面的渲染过程
### 网络
- http协议。说一下200和304的理解和区别
- 怎么解决跨域的。以及后续JSONP的原理和实现以及cors怎么设置
- postMessage原理
- 输入一个URL，Enter之后发生了什么

## 框架
### React
### Vue
- Router
	- Vue router 除了 router-link 怎么实现跳转?
	- Vue router 跳转和 location.href 有什么区别？
- 数据绑定
	- Vue 双向绑定实现原理？
### Angular
### 原理
- 路由
	- 单页应用，如何实现其路由功能
- 你能实现一下双向绑定吗？
## 架构
### 渐进增强
### 模块化开发
### 技术选型
- React 和 Vue 有什么区别？
- Require 与webpack相比，两者打包的异同及优缺点
- 使用框架 ( vue / react 等)带来好处( 相对jQuery )

## 工程实践
### 单元测试
* 常用框架或库
* 如何模拟用户操作
* 如何隔离网络请求
### 端到端测试
* 常用工具
* 如何在 CI 上运行
* 如何保证测试稳定性
* 如何测试样式
### 代码规范
* 常用工具
### 打包工具
- Webpack
	- webpack与grunt、gulp的不同？
	- 与webpack类似的工具还有哪些？谈谈你为什么最终选择（或放弃）使用webpack？
	- 有哪些常见的Loader？他们是解决什么问题的？
	- 有哪些常见的Plugin？他们是解决什么问题的？
	- Loader和Plugin的不同？
	- webpack的构建流程是什么?从读取配置到输出文件这个过程尽量说全
	- 是否写过Loader和Plugin？描述一下编写loader或plugin的思路？
	- webpack的热更新是如何做到的？说明其原理？
	- 如何利用webpack来优化前端性能？（提高性能和体验）
	- 如何提高webpack的构建速度？
	- 怎么配置单页应用？怎么配置多页应用？
	- npm打包时需要注意哪些？如何利用webpack来更好的构建？
	- 如何在vue项目中实现按需加载？
	- webpack的入口文件怎么配置，多个入口怎么分割
	- webpack配置用到webpack.optimize.UglifyJsPlugin这个插件，有没有觉得压缩速度很慢，有什么办法提升速度
- Gulp
	- gulp自己写过任务吗？还是都用的模块？
	- 实现 gulp 的功能
- Babel
	- Babel的一个插件：transform-runtime以及stage-2，你说一下他们的作用
### 性能优化
- 分页器组件
- 优化方法
	- 页面静态化
	- CDN 加速
	- HTTPDNS
	- 合并文件减少请求
	- 异步加载
	- 缓存
		- 静态资源或者接口等如何做缓存优化
	- Native 缓存
- 页面DOM节点太多，会出现什么问题？如何优化？
### 安全
- 前端安全问题：CSRF和XSS
## 趋势
### Web 3.0
### 微前端
- - - - - 
## 推荐资源
>**推荐者**：[Jimmy Lv](https://github.com/JimmyLv)

[egghead.io](https://egghead.io/lessons) - Bite-sized Web Development Video Tutorials & Training
>前端最权威的视频网站，前沿新技术学习资料都有

[React Resources](https://reactresources.com)
> React 最棒的资源集合，定期更新（会包括以下blogger）

[Kent C. Dodds Blog](https://kentcdodds.com)
>Kent 前端testing-library作者，测试领域翘楚

[React.js Examples](https://reactjsexample.com/)
>React 示例，可以看到很多实例和相关组件

[Dan Abramov's Overreacted Blog](https://overreacted.io)
>Redux 作者，React 团队核心成员

[RWieruch](https://www.robinwieruch.de)
>德国专职作者，Road to learn XX 系列电子书

[Cypress Blog](https://cypress-io.ghost.io/blog/)
>E2E 测试框架博客，经常有前端测试相关的文章

[WebStorm Blog](https://blog.jetbrains.com/webstorm)
>工具篇，最强IDE最新动态，如何更快更好写代码