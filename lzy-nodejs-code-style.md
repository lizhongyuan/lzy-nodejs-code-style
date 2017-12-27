# Node.js 代码规范简介
## Table of contents
### 格式
* [2空格缩进](#2空格缩进)
* [Newlines](#newlines)
* [No trailing whitespace](#no-trailing-whitespace)
* [Use single quotes](#use-single-quotes)
### 2空格缩进

使用2个空格作为缩进, 不要混用tab和空格
### Newlines

使用UNIX类型换行符(`\n`), 并且换行符作为最后文件的最后一个字符. 禁止使用Windows类型的换行符(`\r\n`)
### No trailing whitespace

禁止使用尾随空格
### Use single quotes

使用单引号, 除非处理JSON.

*正确:*

```js
var foo = 'bar';
```

*错误:*

```js
var foo = "bar";
```
