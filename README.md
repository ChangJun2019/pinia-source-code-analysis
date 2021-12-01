# pinia-source-code-read

## pinia 是什么？

[pinia](https://pinia.esm.dev/introduction.html) 是一个 Vue 的极轻量的状态管理库，它依赖于新的响应式系统（ reactivity ）和 composition api 构建，最近受到了很多的关注，作者也是 Vue 的团队成员。它有着一下优点：

- 完整的 TypeScript 支持
- API设计非常友好，使用足够简单。（接近 [Vuex 5 RFC](https://github.com/vuejs/rfcs/discussions/270)）
- 模块化设计，支持代码自动拆分。
- 支持 Vue devtools
- 极轻量（1kb 左右）

pinia 的作者声明，pinia 并不是为了替代 Vuex，它旨在让开发者能够容易迁移到 Vuex，未来和 Vuex 融合。详情可以查看 [Comparison with Vuex](https://pinia.esm.dev/introduction.html#comparison-with-vuex)  (Evan You也说了 pinia 是事实上的 Vuex5)

## 这是什么？

这是一份克隆了 [pinia@2.0.4](https://github.com/posva/pinia/releases/tag/pinia%402.0.4) 版本的代码仓库。

我会对其进行阅读和注释，目前已经完成浅阅读。

事实上 pinia 的代码量不是很多，而且 API 也设计的足够简单，因此源码并没有花多久就阅读完了。（ 对于我这样的调试及慢速来说还是相对来说容易理解的 ）

感谢 pinia 这是一个非常好的状态管理工具库！

