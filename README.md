# awesome-swift

## 0195-dynamic-member-lookup
>https://github.com/apple/swift-evolution/blob/master/proposals/0195-dynamic-member-lookup.md
>https://juejin.cn/post/6844903621306351624

## 0216-dynamic-callable
>https://github.com/apple/swift-evolution/blob/master/proposals/0216-dynamic-callable.md <br>
>https://www.jianshu.com/p/49b8e6f6a51d <br>
>https://medium.com/swlh/calling-ios-and-macos-hidden-api-in-style-1a924f244ad1 <br>

## 0296-async-await
>https://github.com/apple/swift-evolution/blob/main/proposals/0296-async-await.md
>https://www.enekoalonso.com/articles/getting-started-with-async-await-in-swift
>https://developer.apple.com/library/archive/documentation/ToolsLanguages/Conceptual/Xcode_Overview/AlternativeToolchains.html
>https://ordinarycoding.com/articles/managing-toolchains-in-xcode/

## swift5.2~5.4
>[Swift 5.2到5.4新特性整理](https://hicc.pro/p/swift/whats-new-in-swift-5-2-to-5-4) <br>

## swift5.5
>[Swift 5.5 新特性](https://segmentfault.com/a/1190000040382170) <br>
>[Swift 5.5 新特性](https://hicc.pro/p/swift/whats-new-in-swift-5-5) <br>

## 0054-abolish-iuo
>[0054-abolish-iuo](https://github.com/apple/swift-evolution/blob/master/proposals/0054-abolish-iuo.md) <br>
>[Coercion of implicitly unwrappable value]<https://useyourloaf.com/blog/coercion-of-implicitly-unwrappable-value/> <br>

## 0289-result-builders
>[Result builders](https://github.com/apple/swift-evolution/blob/main/proposals/0289-result-builders.md) <br>
>[NSAttributedStringBuilder](https://github.com/ethanhuang13/NSAttributedStringBuilder) <br>
>[使用 Swift 特性 Result Builder 定制 DSL](https://mp.weixin.qq.com/s/Rq1c26L9AnjdOtPSA96Ovw) <br>

## KeyPath
>[KeyPath在Swift中的妙用](https://juejin.cn/post/6844903717511102472) <br>

## 0306-actors
>[0306-actors](https://github.com/apple/swift-evolution/blob/main/proposals/0306-actors.md) <br>
>[【译】SE-0306 Actors](https://kemchenj.github.io/2021-04-25/) <br>

## swift concurrency
>[Swift 并发初步](https://onevcat.com/2021/07/swift-concurrency/) <br>
>[Swift 结构化并发](https://onevcat.com/2021/09/structured-concurrency/) <br>
>[What role do Tasks play within Swift’s concurrency system?](https://www.swiftbysundell.com/articles/the-role-tasks-play-in-swift-concurrency/#context-inheritance) <br>
>[Async and Await in Swift 5.5](https://mp.weixin.qq.com/s/DopuYyy479eSjgns3iaWaw) <br>
>[WWDC21 Explore structured concurrency in Swift](https://juejin.cn/post/6973336267794677791) <br>
>[Using AsyncSequence in Swift](https://www.andyibanez.com/posts/using-asyncsequence-in-swift/) <br>
>[https://www.imgeek.org/article/825359559](https://www.imgeek.org/article/825359559) <br>
>[AsyncExtensions](https://github.com/AsyncCommunity/AsyncExtensions) <br>
>[闲话 Swift 协程](https://www.bennyhuo.com/book/swift-coroutines) <br>

## Property Wrappers
>[[译]Swift中的原子属性装饰器](https://hicc.pro/p/blog/atomic-property-wrapper-in-swift) <br>
>[Property Wrappers in Swift explained with code examples](https://www.avanderlee.com/swift/property-wrappers/) <br>
>[Projecting a Value From a Property Wrapper](https://www.avanderlee.com/swift/property-wrappers/#projecting-a-value-from-a-property-wrapper) <br>
>[Accessing a property wrapper’s enclosing instance](https://www.avanderlee.com/swift/property-wrappers/#accessing-a-property-wrappers-enclosing-instance) <br>
>[Attaching Property Wrappers to function and closure parameters](https://www.avanderlee.com/swift/property-wrappers/#attaching-property-wrappers-to-function-and-closure-parameters) <br>


## ABI
>[Swift ABI 稳定对我们到底意味着什么](https://onevcat.com/2019/02/swift-abi/) <br>
>app 尺寸会变小
是的，但是这是 Apple 通过 App Thinning 帮我们完成的，不需要你操心。在提交 app 时，Apple 将会按照 iOS 系统创建不同的下载包。对于 iOS 12.2 的系统，因为它们预装了 Swift 5 的 runtime，所以不再需要 Swift 的库，它们会被从 app bundle 中删掉。对于 iOS 12.2 以下的系统，外甥打灯笼，照旧。
一个新创建的空 app，针对 iOS 12.2 打包出来压缩后的下载大小是 26KB，而对 iOS 12.0 则是 2.4MB。如果你使用了很多标准库里的东西，那这个差距会更大 (因为没有用到的标准库的符号会被 strip 掉)，对于一个比较有规模的 app 来说，一般可以减小 10M 左右的体积。

## Algorithms&Collection
>[初探 Swift 算法和集合](https://mp.weixin.qq.com/s/WpvuuUXQPwBHZpk8OmuPDg) <br>


## Loops
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
## SE-0302 Sendable 和 @Sendable 闭包
>[【译】SE-0302 Sendable 和 @Sendable 闭包](https://kemchenj.github.io/2022-01-07/) <br>

## Array
>[Swift子数组提取性能优化分析](https://mp.weixin.qq.com/s?__biz=MzU3NTY3MTQzMg==&mid=2247527626&idx=1&sn=a67bc5de7da51bc632d10a7eca50a345&scene=21#wechat_redirect) <br>

## protocols
>[Combining protocols in Swift](https://www.swiftbysundell.com/articles/combining-protocols-in-swift/) <br>
>[Abstract types and methods in Swift](https://www.swiftbysundell.com/articles/abstract-types-and-methods/) <br>
>[PROTOCOL & GENERIC IN SWIFT](http://nonomori.bitcron.com/post/protocolandgenericinswift/readme) <br>
## Opaque Types some && swift 多态度
>[some](https://juejin.cn/post/6844903862290104327) <br>
>[Swift 的类型多态](https://blog.mzying.com/index.php/archives/274/) <br>



## AnyObject, Any, and any
>[AnyObject, Any, and any: When to use which?](https://www.avanderlee.com/swift/anyobject-any/) <br>

## Swift-Tips
>[SwiftEchoes-Tips](https://github.com/Luur/SwiftEchoes-Tips) <br>
>[swift-tips](https://github.com/JohnSundell/SwiftTips) <br>

## swift 5.6
>[new in Swift 5.6](https://www.hackingwithswift.com/articles/247/whats-new-in-swift-5-6) <br>
SE-0335 introduces a new any keyword to mark existential types
SE-0315 introduces the concept of type placeholders
SE-0290 introduces an inverted form of #available called #unavailable
>[Swift 5.6 新特性](https://juejin.cn/post/7077369199626027039) <br>


## swift 5.7
>[Swift 5.7新特性 (上)](https://juejin.cn/post/7107058234409615373) <br>
>[Swift 5.7 新特性（下）](https://juejin.cn/post/7108562023876657189) <br>
