# 编程与类型系统（Programming with Types） 读书笔记

简单的总结一下，总体感觉还是挺适合作为 TypeScript 的进阶读物的，没有太高的理解成本（除了函数式相关的部分），能够很快读完（我用了 6h 左右），对我来说主要包括这么几个收益：

- 类型、类型安全、类型系统
- 协变、逆变、不变、双变
- 函数式：函子、单子等

但是也有一些感觉不太对的，比如在后面的几章使用了大量的章节讲述 Generator、Iterator、Mixin 等 “逻辑层” 的进阶代码，虽然这些示例确实都是强类型的，但是我感觉和类型、类型系统没什么关系，都是应用层的？比如你不可能通过如何填充类型参数学习到 TS 的类型检查体系，但话又说回来，这本书确实不是专门为了 TS 而写的，只是恰好选择了 TS 作为示例代码。

另外，我感觉作者应该有很强的函数式编程背景，文章中有较多的篇幅设计了包括函子、单子、幺半群等在内的这些函数式编程概念，并不包含在我阅读这本书的目的中。而对于我有兴趣的，如协变逆变，其实不如我之前写的 「[知其然，知其所以然：TypeScript 中的协变与逆变](https://juejin.cn/post/7050099282317148174)」 更详细，但这些确实和 「类型」 更沾边。看起来还是需要了解 TypeScript 专有的类型系统。

- 笔记见 [notes](docs/index.md)，你也可以运行 `pnpm docs:dev` 来获得更好的阅读体验。
