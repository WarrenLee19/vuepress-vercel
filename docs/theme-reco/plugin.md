---
title: 基于deno和react实现同构SSR应用程序
date: 2021-07-28
---

### SSR-Deno
是基于deno和react实现同构应用程序，在不需要webpack和node完成一个SSR应用程序
[Gitee ssr-deno地址](https://gitee.com/WarrenLee19/ssr-deno) 觉得不错的可以star
#### 主要实现：
1.deno bundler ：自带打包和 tree shaking功能，可以将我们的代码打包成单文件
2.ReactDom.hydrate :与 render() 相同，但它用于在 ReactDOMServer 渲染的容器中对 HTML 的内容进行 hydrate 操作
