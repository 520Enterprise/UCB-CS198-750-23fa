# HTML

## Common HTML Tags

调整字体的:

- Bold: `<b> </b>` OR `<strong> </strong>`
- Italics: `<i> </i>`` OR `<em> </em>`
- Underline:` <u> </u>`

# API



# HW6

调用 npm 的时候记得用windows自带的终端(开管理员权限)，GitBash 总是有一些奇奇怪怪的毛病

箭头函数语法

```javascript
(param1, param2, …, paramN) => { statements }
(param1, param2, …, paramN) => expression
//相当于：(param1, param2, …, paramN) =>{ return expression; }

// 当只有一个参数时，圆括号是可选的：
(singleParam) => { statements }
singleParam => { statements }

// 没有参数的函数应该写成一对圆括号。
() => { statements }
```

有了 npm install 我们就没必要打包上传巨大的 node_modules 文件夹了

roote 的定义: `app.METHOD(PATH, HANDLER)`，其中

 哪里：

- `app` 是 的 `express` 实例。
- `METHOD` 是一个小写的 HTTP 请求方法。
- `PATH` 是服务器上的路径。
- `HANDLER` 是 roote 匹配时执行的函数。

具体地看这个作业的代码就懂了
