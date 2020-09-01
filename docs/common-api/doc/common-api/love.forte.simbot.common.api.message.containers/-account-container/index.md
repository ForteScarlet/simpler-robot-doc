//[common-api](../../index.md)/[love.forte.simbot.common.api.message.containers](../index.md)/[AccountContainer](index.md)



# AccountContainer  
 [JVM] 一个账号信息容器, 继承了 [用户名称容器](../-account-name-container/index.md)[用户头像容器](../-account-avatar-container/index.md)[用户账号容器](../-account-code-container/index.md)  
  
interface [AccountContainer](index.md) : [AccountNameContainer](../-account-name-container/index.md), [AccountAvatarContainer](../-account-avatar-container/index.md), [AccountCodeContainer](../-account-code-container/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)| [JVM]  <br>Content  <br>open operator override fun [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)| [JVM]  <br>Content  <br>open override fun [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)| [JVM]  <br>Content  <br>open override fun [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [avatar](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/avatar/#/PointingToDeclaration/)|  [JVM] 得到账号的头像地址. 一般来讲为null的可能性很小abstract override val [avatar](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/avatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [code](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/code/#/PointingToDeclaration/)|  [JVM] 账号abstract override val [code](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/code/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [codeNumber](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/codeNumber/#/PointingToDeclaration/)|  [JVM] 账号的数字值。（如果能作为数字的话）open override val [codeNumber](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/codeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [nickname](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/nickname/#/PointingToDeclaration/)|  [JVM] 昵称abstract override val [nickname](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/nickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [nicknameAndRemark](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/nicknameAndRemark/#/PointingToDeclaration/)|  [JVM] 昵称与备注, 返回一个账号(备注)?格式的字符串. 例如：<ul><li>张三(张三的备注)</li><li>李四 (没有备注)</li></ul>open override val [nicknameAndRemark](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/nicknameAndRemark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [remark](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/remark/#/PointingToDeclaration/)|  [JVM] 好友备注或群名片abstract override val [remark](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/remark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [remarkOrNickname](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/remarkOrNickname/#/PointingToDeclaration/)|  [JVM] 如果有备注则得到备注，否则得到昵称open override val [remarkOrNickname](index.md#love.forte.simbot.common.api.message.containers/AccountContainer/remarkOrNickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>


## Inheritors  
  
|  Name| 
|---|
| [MsgGet](../../love.forte.simbot.common.api.message/-msg-get/index.md)

