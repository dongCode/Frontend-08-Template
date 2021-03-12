# 前十周学习总结

>算法加强了自身对于编程思想的理解，加强了自身编程的乐趣

## 第一阶段：一～五周编程与算法练习

这一阶段主要训练了算法与编程思想，对应每周的学习内容为：

* 三字棋 体会算法带来的乐趣 红绿灯 体会合理组织代码逻辑的乐趣
* 路径搜索算法 体会地图算法
* AST 构建
* 字符串分析算法
* 使用 `Proxy` 简单实现 Vue3 中的双向绑定

## 第二阶段：六～七周重学 `JavaScript`

对应课程组织结构为：

* JS 了解了简单的编译原理  学会了看官方文档

语言语法最基本的要素  

    primitive expressions, which represent the simplest entities the language is concerned with,
    means of combination, by which compound elements are built from simpler ones, and
    means of abstraction, by which compound elements can be named and manipulated as units.

    


## 第三阶段：八～十周浏览器工作原理

浏览器的基础渲染路径为：HTTP 发送请求获取响应内容 -> HTML parse -> CSS computing -> layout -> render 。

1. 定义请求内容
2. 发送请求获取响应内容并并使用状态机进行分析转码
3. 将转码后获取到的 HTML 通过状态机进行 parser
4. HTML 解析的同时，计算对应的样式表并放入 DOM 树上
5. 检测到 `endTag` 时进行 layout。layout 主要实现了 `flex` 布局
6. 使用 images 包进行 DOM 树的绘制

## 总结

编程实践最重要，多动手，多思考。





