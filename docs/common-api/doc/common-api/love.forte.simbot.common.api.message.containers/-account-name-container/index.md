//[common-api](../../index.md)/[love.forte.simbot.common.api.message.containers](../index.md)/[AccountNameContainer](index.md)



# AccountNameContainer  
 [JVM] 账户名称容器，即 [账号昵称容器](../-account-nickname-container/index.md) 与 [账号备注容器](../-account-remark-container/index.md) 并提供几个默认的整合值:<ul><li>[备注或昵称](index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/remarkOrNickname/#/PointingToDeclaration/)</li><li>[昵称与备注](index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/nicknameAndRemark/#/PointingToDeclaration/)</li></ul>  
  
interface [AccountNameContainer](index.md) : [AccountNicknameContainer](../-account-nickname-container/index.md), [AccountRemarkContainer](../-account-remark-container/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)| [JVM]  <br>Content  <br>open operator override fun [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)| [JVM]  <br>Content  <br>open override fun [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)| [JVM]  <br>Content  <br>open override fun [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [nickname](index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/nickname/#/PointingToDeclaration/)|  [JVM] 昵称abstract override val [nickname](index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/nickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [nicknameAndRemark](index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/nicknameAndRemark/#/PointingToDeclaration/)|  [JVM] 昵称与备注, 返回一个账号(备注)?格式的字符串. 例如：<ul><li>张三(张三的备注)</li><li>李四 (没有备注)</li></ul>open val [nicknameAndRemark](index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/nicknameAndRemark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [remark](index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/remark/#/PointingToDeclaration/)|  [JVM] 好友备注或群名片abstract override val [remark](index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/remark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [remarkOrNickname](index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/remarkOrNickname/#/PointingToDeclaration/)|  [JVM] 如果有备注则得到备注，否则得到昵称open val [remarkOrNickname](index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/remarkOrNickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>


## Inheritors  
  
|  Name| 
|---|
| [AccountContainer](../-account-container/index.md)

