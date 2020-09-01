//[common-api](../../index.md)/[love.forte.simbot.common.api.message](../index.md)/[MessageEventGet](index.md)



# MessageEventGet  
 [JVM] 与消息有关的事件 除了[MsgGet](../-msg-get/index.md)中的东西以外, 还要有一个[FlagContainer](../../love.forte.simbot.common.api.message.containers/-flag-container/index.md)。 但是一般来讲, [FlagContainer.flag](../../love.forte.simbot.common.api.message.containers/-flag-container/index.md#love.forte.simbot.common.api.message.containers/FlagContainer/flag/#/PointingToDeclaration/) 都可以用 [id](index.md#love.forte.simbot.common.api.message/MessageEventGet/id/#/PointingToDeclaration/)来代替。 因此 [flag](index.md#love.forte.simbot.common.api.message/MessageEventGet/flag/#/PointingToDeclaration/)提供为默认方法并使用[id](index.md#love.forte.simbot.common.api.message/MessageEventGet/id/#/PointingToDeclaration/)作为返回值。如果有特殊需要则重写  
  
interface [MessageEventGet](index.md) : [MsgGet](../-msg-get/index.md), [FlagContainer](../../love.forte.simbot.common.api.message.containers/-flag-container/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)| [JVM]  <br>Content  <br>open operator override fun [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)| [JVM]  <br>Content  <br>open override fun [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../-msg-get/to-string.md)| [JVM]  <br>Content  <br>abstract override fun [toString](../-msg-get/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [avatar](index.md#love.forte.simbot.common.api.message/MessageEventGet/avatar/#/PointingToDeclaration/)|  [JVM] 得到账号的头像地址. 一般来讲为null的可能性很小abstract override val [avatar](index.md#love.forte.simbot.common.api.message/MessageEventGet/avatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [botAvatar](index.md#love.forte.simbot.common.api.message/MessageEventGet/botAvatar/#/PointingToDeclaration/)|  [JVM] 机器人的头像abstract override val [botAvatar](index.md#love.forte.simbot.common.api.message/MessageEventGet/botAvatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [botCode](index.md#love.forte.simbot.common.api.message/MessageEventGet/botCode/#/PointingToDeclaration/)|  [JVM] 当前的bot的账号abstract override val [botCode](index.md#love.forte.simbot.common.api.message/MessageEventGet/botCode/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [botCodeNumber](index.md#love.forte.simbot.common.api.message/MessageEventGet/botCodeNumber/#/PointingToDeclaration/)|  [JVM] 得到[botCode](index.md#love.forte.simbot.common.api.message/MessageEventGet/botCode/#/PointingToDeclaration/)的[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)类型。如果可以作为数字的话。open override val [botCodeNumber](index.md#love.forte.simbot.common.api.message/MessageEventGet/botCodeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [botName](index.md#love.forte.simbot.common.api.message/MessageEventGet/botName/#/PointingToDeclaration/)|  [JVM] 机器人的名称abstract override val [botName](index.md#love.forte.simbot.common.api.message/MessageEventGet/botName/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [code](index.md#love.forte.simbot.common.api.message/MessageEventGet/code/#/PointingToDeclaration/)|  [JVM] 账号abstract override val [code](index.md#love.forte.simbot.common.api.message/MessageEventGet/code/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [codeNumber](index.md#love.forte.simbot.common.api.message/MessageEventGet/codeNumber/#/PointingToDeclaration/)|  [JVM] 账号的数字值。（如果能作为数字的话）open override val [codeNumber](index.md#love.forte.simbot.common.api.message/MessageEventGet/codeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [flag](index.md#love.forte.simbot.common.api.message/MessageEventGet/flag/#/PointingToDeclaration/)|  [JVM] 默认使用[id](index.md#love.forte.simbot.common.api.message/MessageEventGet/id/#/PointingToDeclaration/)实现[flag](index.md#love.forte.simbot.common.api.message/MessageEventGet/flag/#/PointingToDeclaration/)open override val [flag](index.md#love.forte.simbot.common.api.message/MessageEventGet/flag/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [id](index.md#love.forte.simbot.common.api.message/MessageEventGet/id/#/PointingToDeclaration/)|  [JVM] 当前监听事件消息的ID。一般情况下应当是一个唯一ID。abstract override val [id](index.md#love.forte.simbot.common.api.message/MessageEventGet/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [msg](index.md#love.forte.simbot.common.api.message/MessageEventGet/msg/#/PointingToDeclaration/)|  [JVM] 监听消息的消息正文文本abstract override var [msg](index.md#love.forte.simbot.common.api.message/MessageEventGet/msg/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [nickname](index.md#love.forte.simbot.common.api.message/MessageEventGet/nickname/#/PointingToDeclaration/)|  [JVM] 昵称abstract override val [nickname](index.md#love.forte.simbot.common.api.message/MessageEventGet/nickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [nicknameAndRemark](index.md#love.forte.simbot.common.api.message/MessageEventGet/nicknameAndRemark/#/PointingToDeclaration/)|  [JVM] 昵称与备注, 返回一个账号(备注)?格式的字符串. 例如：<ul><li>张三(张三的备注)</li><li>李四 (没有备注)</li></ul>open override val [nicknameAndRemark](index.md#love.forte.simbot.common.api.message/MessageEventGet/nicknameAndRemark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [originalData](index.md#love.forte.simbot.common.api.message/MessageEventGet/originalData/#/PointingToDeclaration/)|  [JVM] 得到原始数据字符串。 数据不应该为null。abstract override val [originalData](index.md#love.forte.simbot.common.api.message/MessageEventGet/originalData/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [remark](index.md#love.forte.simbot.common.api.message/MessageEventGet/remark/#/PointingToDeclaration/)|  [JVM] 好友备注或群名片abstract override val [remark](index.md#love.forte.simbot.common.api.message/MessageEventGet/remark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [remarkOrNickname](index.md#love.forte.simbot.common.api.message/MessageEventGet/remarkOrNickname/#/PointingToDeclaration/)|  [JVM] 如果有备注则得到备注，否则得到昵称open override val [remarkOrNickname](index.md#love.forte.simbot.common.api.message/MessageEventGet/remarkOrNickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [time](index.md#love.forte.simbot.common.api.message/MessageEventGet/time/#/PointingToDeclaration/)|  [JVM] 消息接收到的时间。一般是一个时间戳。abstract override val [time](index.md#love.forte.simbot.common.api.message/MessageEventGet/time/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [PrivateMsg](../-private-msg/index.md)
| [GroupMsg](../-group-msg/index.md)

