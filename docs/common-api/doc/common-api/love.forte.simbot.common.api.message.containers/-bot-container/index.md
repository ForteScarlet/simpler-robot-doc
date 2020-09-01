//[common-api](../../index.md)/[love.forte.simbot.common.api.message.containers](../index.md)/[BotContainer](index.md)



# BotContainer  
 [JVM] 机器人基础信息容器, 其实现了 [机器人账号容器](../-bot-code-container/index.md)[机器人名称容器](../-bot-name-container/index.md)[机器人头像容器](../-bot-avatar-container/index.md)  
  
interface [BotContainer](index.md) : [BotCodeContainer](../-bot-code-container/index.md), [BotNameContainer](../-bot-name-container/index.md), [BotAvatarContainer](../-bot-avatar-container/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)| [JVM]  <br>Content  <br>open operator override fun [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)| [JVM]  <br>Content  <br>open override fun [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)| [JVM]  <br>Content  <br>open override fun [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [botAvatar](index.md#love.forte.simbot.common.api.message.containers/BotContainer/botAvatar/#/PointingToDeclaration/)|  [JVM] 机器人的头像abstract override val [botAvatar](index.md#love.forte.simbot.common.api.message.containers/BotContainer/botAvatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [botCode](index.md#love.forte.simbot.common.api.message.containers/BotContainer/botCode/#/PointingToDeclaration/)|  [JVM] 当前的bot的账号abstract override val [botCode](index.md#love.forte.simbot.common.api.message.containers/BotContainer/botCode/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [botCodeNumber](index.md#love.forte.simbot.common.api.message.containers/BotContainer/botCodeNumber/#/PointingToDeclaration/)|  [JVM] 得到[botCode](index.md#love.forte.simbot.common.api.message.containers/BotContainer/botCode/#/PointingToDeclaration/)的[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)类型。如果可以作为数字的话。open override val [botCodeNumber](index.md#love.forte.simbot.common.api.message.containers/BotContainer/botCodeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [botName](index.md#love.forte.simbot.common.api.message.containers/BotContainer/botName/#/PointingToDeclaration/)|  [JVM] 机器人的名称abstract override val [botName](index.md#love.forte.simbot.common.api.message.containers/BotContainer/botName/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [MsgGet](../../love.forte.simbot.common.api.message/-msg-get/index.md)

