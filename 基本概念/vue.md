vue是一个运行时+编译时的框架
```
vue通过compiler解析html模板,生成render函数，然后通过runtime解析render,从而挂载真实dom


对于dom渲染而言 可以被分成两个部分
1. 初次渲染 我们可以把它叫做挂载
2. 更新渲染 我们可以把它叫做打补丁


对于vue3 三大模块
1. 响应式: reactivity
2. 运行时: runtime
3. 编译器: compiler