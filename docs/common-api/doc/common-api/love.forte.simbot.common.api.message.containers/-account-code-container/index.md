//[common-api](../../index.md)/[love.forte.simbot.common.api.message.containers](../index.md)/[AccountCodeContainer](index.md)



# AccountCodeContainer  
 [JVM] 账户号码容器。定义可以得到一个账号的号码 其中,[codeNumber](index.md#love.forte.simbot.common.api.message.containers/AccountCodeContainer/codeNumber/#/PointingToDeclaration/)默认为[code](index.md#love.forte.simbot.common.api.message.containers/AccountCodeContainer/code/#/PointingToDeclaration/).[toLong](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/index.html)  
  
interface [AccountCodeContainer](index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)| [JVM]  <br>Content  <br>open operator override fun [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)| [JVM]  <br>Content  <br>open override fun [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)| [JVM]  <br>Content  <br>open override fun [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [code](index.md#love.forte.simbot.common.api.message.containers/AccountCodeContainer/code/#/PointingToDeclaration/)|  [JVM] 账号abstract val [code](index.md#love.forte.simbot.common.api.message.containers/AccountCodeContainer/code/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [codeNumber](index.md#love.forte.simbot.common.api.message.containers/AccountCodeContainer/codeNumber/#/PointingToDeclaration/)|  [JVM] 账号的数字值。（如果能作为数字的话）open val [codeNumber](index.md#love.forte.simbot.common.api.message.containers/AccountCodeContainer/codeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AccountContainer](../-account-container/index.md)

