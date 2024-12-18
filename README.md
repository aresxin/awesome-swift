# awesome-swift

## Contents
- [Swift Release](#Swift-Release)
- [Swift Evolution](#Swift-Evolution)
- [POP](#POP)
- [Concurrency](#Concurrency)
- [Combine](#Combine)
- [Regex](#Regex)
- [Swift Macros](#Swift-Macros)
- [Swift Charts](#Swift-Charts)
- [Command line app in Swift](#CommandLineApp)
- [Best Practices](#Best-Practices)
- [Swift-Tips](#Swift-Tips)
- [awesome](#awesome)
- [Other](#Other)

## Swift-Release

### swift5.2~5.4
>[Swift 5.2到5.4新特性整理](https://hicc.pro/p/swift/whats-new-in-swift-5-2-to-5-4) <br>

### swift5.5
>[Swift 5.5 新特性](https://segmentfault.com/a/1190000040382170) <br>
>[Swift 5.5 新特性](https://hicc.pro/p/swift/whats-new-in-swift-5-5) <br>

### swift 5.6
>[new in Swift 5.6](https://www.hackingwithswift.com/articles/247/whats-new-in-swift-5-6) <br>
SE-0335 introduces a new any keyword to mark existential types
SE-0315 introduces the concept of type placeholders
SE-0290 introduces an inverted form of #available called #unavailable <br>
>[Swift 5.6 新特性](https://juejin.cn/post/7077369199626027039) <br>

### swift 5.7
>[Swift 5.7 新特性介绍](https://mp.weixin.qq.com/s/gzzme538BJqh-yUcGr-AZQ) <br>
>[Swift 5.7新特性 (上)](https://juejin.cn/post/7107058234409615373) <br>
>[Swift 5.7 新特性（下）](https://juejin.cn/post/7108562023876657189) <br>
>[Combining opaque return types with primary associated types](https://www.swiftbysundell.com/articles/opaque-return-types-primary-associated-types/) <br>

#### 5.7 Embrace Swift generics
>[Embrace Swift generics](https://developer.apple.com/videos/play/wwdc2022/110352) <br>
>[Using the ‘some’ and ‘any’ keywords to reference generic protocols in Swift 5.7](https://www.swiftbysundell.com/articles/referencing-generic-protocols-with-some-and-any-keywords/) <br>

#### 5.7 Design protocol interfaces in Swift
>[Design protocol interfaces in Swift](https://developer.apple.com/videos/play/wwdc2022/110353) <br>
>[Swift_5.7_Generics](https://gist.github.com/protspace/eaeebc090d2c4c16466e45418cad0afb) <br>
>[Design protocol interfaces in Swift](https://www.wwdcnotes.com/notes/wwdc22/110353/) <br>

### Swift 5.8
[#file behavior change in Swift 5.8](https://sarunw.com/posts/file-behavior-change/) <br>

### Swift 5.9
[What’s new in Swift 5.9](https://www.hackingwithswift.com/articles/258/whats-new-in-swift-5-9) <br>
[Swift 5.9 有哪些新特性（一）](https://blog.csdn.net/qq_36478920/article/details/131241997) <br>

---
---


## Swift-Evolution

### 0195-dynamic-member-lookup
>https://github.com/apple/swift-evolution/blob/master/proposals/0195-dynamic-member-lookup.md
>https://juejin.cn/post/6844903621306351624


### 0216-dynamic-callable
>https://github.com/apple/swift-evolution/blob/master/proposals/0216-dynamic-callable.md <br>
>https://www.jianshu.com/p/49b8e6f6a51d <br>
>https://medium.com/swlh/calling-ios-and-macos-hidden-api-in-style-1a924f244ad1 <br>


### 0296-async-await
>https://github.com/apple/swift-evolution/blob/main/proposals/0296-async-await.md
>https://www.enekoalonso.com/articles/getting-started-with-async-await-in-swift
>https://developer.apple.com/library/archive/documentation/ToolsLanguages/Conceptual/Xcode_Overview/AlternativeToolchains.html
>https://ordinarycoding.com/articles/managing-toolchains-in-xcode/


### 0054-abolish-iuo
>[0054-abolish-iuo](https://github.com/apple/swift-evolution/blob/master/proposals/0054-abolish-iuo.md) <br>
>[Coercion of implicitly unwrappable value]<https://useyourloaf.com/blog/coercion-of-implicitly-unwrappable-value/> <br>


### 0289-result-builders
>[Result builders](https://github.com/apple/swift-evolution/blob/main/proposals/0289-result-builders.md) <br>
>[NSAttributedStringBuilder](https://github.com/ethanhuang13/NSAttributedStringBuilder) <br>
>[使用 Swift 特性 Result Builder 定制 DSL](https://mp.weixin.qq.com/s/Rq1c26L9AnjdOtPSA96Ovw) <br>
>[ViewBuilder 研究（上）—— 掌握 Result builders](https://mp.weixin.qq.com/s?__biz=MzU1Njg1NDg5NQ==&mid=2247484411&idx=1&sn=370851b6f34e06067da3fdfeea366c90&scene=21#wechat_redirect) <br>
>[ViewBuilder 研究（下） —— 从模仿中学习](https://mp.weixin.qq.com/s?__biz=MzU1Njg1NDg5NQ==&mid=2247484421&idx=1&sn=33e14c8351f27323d58050a95b35acd9&chksm=fc3fff05cb48761346c9906fd3a9227bd404589b06c66cd57dd90cbf34cca2f37525d533cb3b&cur_album_id=2007635589558304775&scene=189#wechat_redirect) <br>
>[result-builders/](https://www.avanderlee.com/swift/result-builders/) <br>


### [0161-key-paths](https://github.com/apple/swift-evolution/blob/main/proposals/0161-key-paths.md)
>[KeyPath在Swift中的妙用](https://juejin.cn/post/6844903717511102472) <br>
>[Dynamic Member Lookup combined with key paths in Swift](https://www.avanderlee.com/swift/dynamic-member-lookup/) <br>


### 0306-actors
>[0306-actors](https://github.com/apple/swift-evolution/blob/main/proposals/0306-actors.md) <br>
>[【译】SE-0306 Actors](https://kemchenj.github.io/2021-04-25/) <br>



### [0258-property-wrappers](https://github.com/apple/swift-evolution/blob/main/proposals/0258-property-wrappers.md)
>[[译]Swift中的原子属性装饰器](https://hicc.pro/p/blog/atomic-property-wrapper-in-swift) <br>
>[Property Wrappers in Swift explained with code examples](https://www.avanderlee.com/swift/property-wrappers/) <br>
>[Projecting a Value From a Property Wrapper](https://www.avanderlee.com/swift/property-wrappers/#projecting-a-value-from-a-property-wrapper) <br>
>[Accessing a property wrapper’s enclosing instance](https://www.avanderlee.com/swift/property-wrappers/#accessing-a-property-wrappers-enclosing-instance) <br>
>[Attaching Property Wrappers to function and closure parameters](https://www.avanderlee.com/swift/property-wrappers/#attaching-property-wrappers-to-function-and-closure-parameters) <br>

### 0393-parameter-packs
[0393-parameter-packs](https://github.com/apple/swift-evolution/blob/main/proposals/0393-parameter-packs.md) <br>
[Generalize APIs with parameter packs](https://developer.apple.com/videos/play/wwdc2023/10168) <br>
[Value and Type Parameter Packs](https://www.hackingwithswift.com/swift/5.9/variadic-generics) <br>

### SE-0302 Sendable 和 @Sendable 闭包
>[【译】SE-0302 Sendable 和 @Sendable 闭包](https://kemchenj.github.io/2022-01-07/) <br>

### [0335-existential-any](https://github.com/apple/swift-evolution/blob/main/proposals/0335-existential-any.md)
[Existential any in Swift explained with code examples](https://www.avanderlee.com/swift/existential-any/) <br>
[Some keyword in Swift: Opaque types explained with code examples](https://www.avanderlee.com/swift/some-opaque-types/) <br>


### dynamicReplacement
[dynamicReplacement](https://github.com/apple/swift/blob/main/test/attr/dynamicReplacement.swift) <br>
[Swift Native method swizzling](https://www.guardsquare.com/blog/swift-native-method-swizzling) <br>
[Swift 5 Method Swizzling, @_dynamicReplacement](https://www.jianshu.com/p/12b64469dc6c) <br>

---
---

## POP
>[Combining protocols in Swift](https://www.swiftbysundell.com/articles/combining-protocols-in-swift/) <br>
>[Abstract types and methods in Swift](https://www.swiftbysundell.com/articles/abstract-types-and-methods/) (讨论面向对象与面向协议什么时候使用更合理)<br>
>[Alternatives to protocols in Swift](https://www.swiftbysundell.com/articles/alternatives-to-protocols-in-swift/#classes-and-inherita) (讨论除了协议以外的其它选择比如枚举喝范型或者多个子协议)<br>
>[PROTOCOL & GENERIC IN SWIFT](http://nonomori.bitcron.com/post/protocolandgenericinswift/readme) <br>
>[Why can’t certain protocols, like Equatable and Hashable, be referenced directly?](https://www.swiftbysundell.com/questions/referencing-generic-protocols/) <br>
>[Different flavors of type erasure in Swift](https://www.swiftbysundell.com/articles/different-flavors-of-type-erasure-in-swift/#external-specialization) <br>
>[Using generic type constraints in Swift](https://www.swiftbysundell.com/articles/using-generic-type-constraints-in-swift-4/) <br>
>[Type erasure using closures in Swift](https://www.swiftbysundell.com/articles/type-erasure-using-closures-in-swift/) <br>
>[Avoiding race conditions in Swift](https://www.swiftbysundell.com/articles/avoiding-race-conditions-in-swift/) <br>
>[Swift 中的幻象类型](https://mp.weixin.qq.com/s?__biz=MzAxNzgzNTgwMw==&mid=2247488350&idx=1&sn=6f6a8f3842a8957f0233e3c618a758c7&scene=21#wechat_redirect) <br>
>[Tagged with Protocols](https://www.swiftbysundell.com/tags/protocols/) <br>
>[Tagged with Generics](https://www.swiftbysundell.com/tags/generics/) <br>

### Opaque Types some && swift 多态度
>[some](https://juejin.cn/post/6844903862290104327) <br>
>[Swift 的类型多态](https://blog.mzying.com/index.php/archives/274/) <br>
>[any and some](https://khorbushko.github.io/article/2024/12/06/any-and-some.html?issue=061&utm_source=fatbobman%20weekly%20issue%2061&utm_medium=email&utm_campaign=fatbobman%20weekly
) <br>


### Dependency Injection in Swift
[Dependency Injection in Swift using latest Swift features](https://www.avanderlee.com/swift/dependency-injection/) <br>

---
---


## Concurrency
### swift concurrency
>[Swift 并发初步](https://onevcat.com/2021/07/swift-concurrency/) <br>
>[Swift 结构化并发](https://onevcat.com/2021/09/structured-concurrency/) <br>
>[What role do Tasks play within Swift’s concurrency system?](https://www.swiftbysundell.com/articles/the-role-tasks-play-in-swift-concurrency/#context-inheritance) <br>
>[Async and Await in Swift 5.5](https://mp.weixin.qq.com/s/DopuYyy479eSjgns3iaWaw) <br>
>[WWDC21 Explore structured concurrency in Swift](https://juejin.cn/post/6973336267794677791) <br>
>[Using AsyncSequence in Swift](https://www.andyibanez.com/posts/using-asyncsequence-in-swift/) <br>
>[https://www.imgeek.org/article/825359559](https://www.imgeek.org/article/825359559) <br>
>[AsyncExtensions](https://github.com/AsyncCommunity/AsyncExtensions) <br>
>[闲话 Swift 协程](https://www.bennyhuo.com/book/swift-coroutines) <br>
>[Limit Swift Concurrency's cooperative pool](https://github.com/apple/swift/blob/main/test/attr/dynamicReplacement.swift) <br>
>[Swift 并发编程：原理探究](https://juejin.cn/post/7109758423805198367) <br>
>[【WWDC21 10132/10133/10134】认识 Swift 中的异步与并发](https://xiaozhuanlan.com/topic/8627905413) <br>
---
---

## Combine
>https://developer.apple.com/documentation/combine <br>
https://theswiftdev.com/urlsession-and-the-combine-framework/ <br>
https://onevcat.com/2020/01/customize-publisher/ <br>
https://www.jianshu.com/p/df8535b40079 <br>
https://www.jianshu.com/p/a9c04a84d911 <br>
https://github.com/cx-org/CombineX <br>
https://github.com/yanglfree/SwiftUI-Combine-Coding <br>
https://learnku.com/articles/36322 <br>
https://zhuanlan.zhihu.com/p/343631974 <br>
[深入浅出 Apple 响应式框架 Combine](https://www.infoq.cn/article/eaq01u5jevuvqfghlqbs) <br>
[Apple 官方异步编程框架：Swift Combine 简介](https://nemocdz.github.io/post/apple-%E5%AE%98%E6%96%B9%E5%BC%82%E6%AD%A5%E7%BC%96%E7%A8%8B%E6%A1%86%E6%9E%B6swift-combine-%E7%AE%80%E4%BB%8B/) <br>
[Apple 官方异步编程框架：Swift Combine 应用](https://nemocdz.github.io/post/apple-%E5%AE%98%E6%96%B9%E5%BC%82%E6%AD%A5%E7%BC%96%E7%A8%8B%E6%A1%86%E6%9E%B6swift-combine-%E5%BA%94%E7%94%A8/) <br>
[Combine 框架，从0到1 —— 5.Combine 提供的发布者(Publishers)](https://www.cnblogs.com/ficow/p/13728001.html) <br>
[UIKit Combine](https://www.jianshu.com/p/b98f3e9c610c) <br>
[Combine 简明教程一： Publisher、Subscriber](https://keisme.cn/Combine-%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B%E4%B8%80%EF%BC%9APublisher%E3%80%81Subscriber.html) <br>
[Combine 简明教程二：自定义 Subscriber、Publisher](https://keisme.cn/Combine-%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B%E4%BA%8C%EF%BC%9A%E8%87%AA%E5%AE%9A%E4%B9%89-Subscriber%E3%80%81Publisher.html) <br>
[Combine 简明教程三：Subject](https://keisme.cn/Combine-%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B%E4%B8%89%EF%BC%9ASubject.html) <br>
[Combine 简明教程四：Operators](https://keisme.cn/Combine-%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B%E5%9B%9B%EF%BC%9AOperators.html) <br>
[从响应式编程到 Combine 实践](https://mp.weixin.qq.com/s?__biz=MzI1MzYzMjE0MQ==&mid=2247495012&idx=1&sn=89b85dd6e2e85d708a2415b78343e9a0&scene=21#wechat_redirect) <br>


---
---

## [Regex](https://developer.apple.com/documentation/swift/regex)
>[Swift 正则速查手册](https://onevcat.com/2022/11/swift-regex/) <br>

---
---

## Swift-Macros
>[WWDC23 10167 - 初见 Swift 宏](https://xiaozhuanlan.com/topic/1403528796) <br>
>[WWDC23 一文看懂 Swift Macro](https://juejin.cn/post/7249888320166903867) <br>
>[Swift-Macros](https://github.com/krzysztofzablocki/Swift-Macros) A curated list of awesome Swift Macros <br>
---
---



## Swift-Charts
> [Swift Charts](https://developer.apple.com/documentation/Charts) Construct and customize charts on every Apple platform. <br>

---
---

## CommandLineApp
>[Lets build a Command line app in Swift](https://medium.com/quick-code/lets-build-a-command-line-app-in-swift-328ce274f1cc) <br>
>[Scripting in Swift: Git Hooks](https://www.polpiella.dev/scripting-in-swift-git-hooks) <br>

---
---

## Best-Practices
### Refactoring Swift
>[Refactoring Swift: Best Practices to succeed](https://www.avanderlee.com/optimization/refactoring-swift-best-practices/) <br>

### Pattern matching
[Pattern matching on error codes](https://oleb.net/blog/2023/catch-error-code/) <br>
[Pattern Matching in Swift](https://oleb.net/blog/2015/09/swift-pattern-matching/) <br>
[Ranges and Intervals in Swift](https://oleb.net/blog/2015/09/swift-ranges-and-intervals/) <br>
[More Pattern Matching Examples](https://oleb.net/blog/2015/09/more-pattern-matching-examples/) <br>


### Wrapping functions in structs
[Wrapping functions in structs](https://paul-samuels.com/blog/2023/03/18/wrapping-functions-in-structs/) <br>

### AnyObject, Any, and any
>[AnyObject, Any, and any: When to use which?](https://www.avanderlee.com/swift/anyobject-any/) <br>

### Loops
>[Loops](https://www.swiftbysundell.com/basics/loops/) <br>

"let names = ["John", "Emma", "Robert", "Julia"]
var string = ""

for name in names where string.count < 8 {
    string.append(name)
}

print(string) // "JohnEmma""

"
for index in names.indices {
    print(index, names[index])
}
"

### Array
>[Swift子数组提取性能优化分析](https://mp.weixin.qq.com/s?__biz=MzU3NTY3MTQzMg==&mid=2247527626&idx=1&sn=a67bc5de7da51bc632d10a7eca50a345&scene=21#wechat_redirect) <br>
>[reduce-in-swift](https://swdevnotes.com/swift/2022/reduce-in-swift/) <br>
>[Lazy Sequences in Swift And How They Work](https://swiftrocks.com/lazy-sequences-in-swift-and-how-they-work) <br>
>[Which Collection?](https://khanlou.com/2022/10/some-collections/) <br>
>[Group and sort Swift collections like a pro](https://danielsaidi.com/blog/2023/04/01/group-and-sort-swift-collections-like-a-pro) <br>


### Range
[Ranges in Swift explained with code examples](https://www.avanderlee.com/swift/ranges-explained/) <br>

### Algorithms&Collection
>[初探 Swift 算法和集合](https://mp.weixin.qq.com/s/WpvuuUXQPwBHZpk8OmuPDg) <br>

### Swift之struct二进制大小分析
https://juejin.cn/post/7191406877819797561 <br>
https://github.com/erduoniba/HDSwiftStructSizeDemo <br>

---
---

## Swift-Tips
>[SwiftEchoes-Tips](https://github.com/Luur/SwiftEchoes-Tips) <br>
>[swift-tips](https://github.com/JohnSundell/SwiftTips) <br>
>https://github.com/vincent-pradeilles/swift-tips <br>

---
---

## awesome
https://github.com/matteocrippa/awesome-swift

---
---

## Other
[《The Swift Programming Language》in Chinese](https://swiftgg.gitbook.io/swift/) <br>

### ABI
>[Swift ABI 稳定对我们到底意味着什么](https://onevcat.com/2019/02/swift-abi/) <br>
>app 尺寸会变小
是的，但是这是 Apple 通过 App Thinning 帮我们完成的，不需要你操心。在提交 app 时，Apple 将会按照 iOS 系统创建不同的下载包。对于 iOS 12.2 的系统，因为它们预装了 Swift 5 的 runtime，所以不再需要 Swift 的库，它们会被从 app bundle 中删掉。对于 iOS 12.2 以下的系统，外甥打灯笼，照旧。
一个新创建的空 app，针对 iOS 12.2 打包出来压缩后的下载大小是 26KB，而对 iOS 12.0 则是 2.4MB。如果你使用了很多标准库里的东西，那这个差距会更大 (因为没有用到的标准库的符号会被 strip 掉)，对于一个比较有规模的 app 来说，一般可以减小 10M 左右的体积。
