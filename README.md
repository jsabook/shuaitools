# 使用方式

## 安装

```bash
npm install wjshuai-tools
```

## 导入

```bash
const shuaitools = require('wjshuai-tools')
```

## 功能

格式化时间

```js
const dtStr = shuaitools.dateFormat(new Date())
console.log(dtStr) //result 2022-06-22 10:39:10
```

转义html

```js
const htmlStr = '<h1 style="color: red;"你好!&copy;<span>小黄!</span></h1>'
const str = shuaitools.htmlEscape(htmlStr)
console.log(str)//&lt;h1 style=&quot: red;&quot;&gt...
```