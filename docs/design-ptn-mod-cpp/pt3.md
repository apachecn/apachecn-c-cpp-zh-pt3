# 第三部分：行为模式

<!-- ch 13~24 -->

当大多数人听说行为模式时，主要是关于动物以及如何让它们做你想做的事情。嗯，在某种程度上，所有的编码都是关于程序做你想做的事情，所以行为软件设计模式涵盖了非常广泛的行为，尽管如此，这些行为在编程中还是很常见的。

作为一个例子，考虑软件工程领域。我们有经过编译的语言，其中包括词法分析、语法分析和无数其他事情(解释器模式)，并且，在为程序构建了抽象语法树(AST)之后，您可能想要分析程序中可能存在的错误(访问者模式)。所有这些行为都很常见，可以用模式来表达，这就是我们今天在这里的原因。

与创造模式(专门关注对象的创建)或结构模式(关注对象的组合/聚合/继承)不同，行为设计模式不遵循一个中心主题。虽然不同的模式之间有某些相似之处(例如，策略和模板方法以不同的方式做同样的事情)，但是大多数模式都提供了解决特定问题的独特方法。