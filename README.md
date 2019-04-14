# laypage

## 简介

- `laypage` 致力于提供极致的分页逻辑，既可轻松胜任异步分页，也可作为页面刷新式分页。

- `laypage` 是从 `layui-v2.4.5` 中提取出来可单独使用的JavaScript分页插件，对于想使用 `laypage` 分页插件但又不想使用 `layui` 框架的开发者提供了方便。

## 快速使用

`laypage` 的使用非常简单，指向一个用于存放分页的容器，通过服务端得到一些初始值，即可完成分页渲染：

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>layPage快速使用</title>
</head>
<body>
 
<div id="test1"></div>
 
<script src="laypage.js"></script>
<script>

//执行一个laypage实例
laypage.render({
  elem: 'test1' //注意，这里的 test1 是 ID，不用加 # 号
  ,count: 50 //数据总数，从服务端得到
});

</script>
</body>
</html>
```

## 基础参数选项

请参考官方文档 [https://www.layui.com/doc/modules/laypage.html](https://www.layui.com/doc/modules/laypage.html#options)
