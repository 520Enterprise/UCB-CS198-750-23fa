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

# HW9

```react
{comments.map((comment, index) => {
    /* Task 3: Use the <Comment> component to render each comment */
    /* YOUR CODE HERE */
    return <Comment key={index} text={comment}/>
})}
```

注意这段代码，其中`key`属性是React中用于标识列表项的唯一性的特殊属性。当我们在渲染动态列表时，每个列表项都需要有一个唯一的`key`值。这样React可以更有效地追踪和管理列表项的更新。

还要注意一个叫做**解构赋值语法**的东西

```javascript
const person = {
  name: 'Alice',
  age: 25,
  address: {
    city: 'New York',
    country: 'USA'
  }
};

// 从对象中提取name和country属性
const { name, address: { country } } = person;

console.log(name); // 输出: Alice
console.log(country); // 输出: USA
```

在上面的例子中，我们定义了一个名为`person`的对象。通过使用解构赋值语法，我们从对象中提取`name`属性并将其赋给`name`变量，同时从`address`属性中提取`country`属性并将其赋给`country`变量。
