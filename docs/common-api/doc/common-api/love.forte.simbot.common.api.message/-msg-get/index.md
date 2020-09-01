//[common-api](../../index.md)/[love.forte.simbot.common.api.message](../index.md)/[MsgGet](index.md)



# MsgGet  
 [JVM] 监听消息的父接口。所有的监听消息都应当实现的容器：<ul><li>[原始信息容器](../../love.forte.simbot.common.api.message.containers/-original-data-container/index.md),</li><li>[bot基础信息容器](../../love.forte.simbot.common.api.message.containers/-bot-container/index.md),</li><li>[用户容器](../../love.forte.simbot.common.api.message.containers/-account-container/index.md)</li></ul>  
  


#### Since  
2.0.0  
  
interface [MsgGet](index.md) : [OriginalDataContainer](../../love.forte.simbot.common.api.message.containers/-original-data-container/index.md), [BotContainer](../../love.forte.simbot.common.api.message.containers/-bot-container/index.md), [AccountContainer](../../love.forte.simbot.common.api.message.containers/-account-container/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)| [JVM]  <br>Content  <br>open operator override fun [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)| [JVM]  <br>Content  <br>open override fun [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](to-string.md)| [JVM]  <br>Brief description  <br>应当重写toString方法  <br>Content  <br>abstract override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [avatar](index.md#love.forte.simbot.common.api.message/MsgGet/avatar/#/PointingToDeclaration/)|  [JVM] 得到账号的头像地址. 一般来讲为null的可能性很小abstract override val [avatar](index.md#love.forte.simbot.common.api.message/MsgGet/avatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [botAvatar](index.md#love.forte.simbot.common.api.message/MsgGet/botAvatar/#/PointingToDeclaration/)|  [JVM] 机器人的头像abstract override val [botAvatar](index.md#love.forte.simbot.common.api.message/MsgGet/botAvatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [botCode](index.md#love.forte.simbot.common.api.message/MsgGet/botCode/#/PointingToDeclaration/)|  [JVM] 当前的bot的账号abstract override val [botCode](index.md#love.forte.simbot.common.api.message/MsgGet/botCode/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [botCodeNumber](index.md#love.forte.simbot.common.api.message/MsgGet/botCodeNumber/#/PointingToDeclaration/)|  [JVM] 得到[botCode](index.md#love.forte.simbot.common.api.message/MsgGet/botCode/#/PointingToDeclaration/)的[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)类型。如果可以作为数字的话。open override val [botCodeNumber](index.md#love.forte.simbot.common.api.message/MsgGet/botCodeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [botName](index.md#love.forte.simbot.common.api.message/MsgGet/botName/#/PointingToDeclaration/)|  [JVM] 机器人的名称abstract override val [botName](index.md#love.forte.simbot.common.api.message/MsgGet/botName/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [code](index.md#love.forte.simbot.common.api.message/MsgGet/code/#/PointingToDeclaration/)|  [JVM] 账号abstract override val [code](index.md#love.forte.simbot.common.api.message/MsgGet/code/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [codeNumber](index.md#love.forte.simbot.common.api.message/MsgGet/codeNumber/#/PointingToDeclaration/)|  [JVM] 账号的数字值。（如果能作为数字的话）open override val [codeNumber](index.md#love.forte.simbot.common.api.message/MsgGet/codeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [id](index.md#love.forte.simbot.common.api.message/MsgGet/id/#/PointingToDeclaration/)|  [JVM] 当前监听事件消息的ID。一般情况下应当是一个唯一ID。abstract val [id](index.md#love.forte.simbot.common.api.message/MsgGet/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [msg](index.md#love.forte.simbot.common.api.message/MsgGet/msg/#/PointingToDeclaration/)|  [JVM] 监听消息的消息正文文本abstract var [msg](index.md#love.forte.simbot.common.api.message/MsgGet/msg/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [nickname](index.md#love.forte.simbot.common.api.message/MsgGet/nickname/#/PointingToDeclaration/)|  [JVM] 昵称abstract override val [nickname](index.md#love.forte.simbot.common.api.message/MsgGet/nickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [nicknameAndRemark](index.md#love.forte.simbot.common.api.message/MsgGet/nicknameAndRemark/#/PointingToDeclaration/)|  [JVM] 昵称与备注, 返回一个账号(备注)?格式的字符串. 例如：<ul><li>张三(张三的备注)</li><li>李四 (没有备注)</li></ul>open override val [nicknameAndRemark](index.md#love.forte.simbot.common.api.message/MsgGet/nicknameAndRemark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [originalData](index.md#love.forte.simbot.common.api.message/MsgGet/originalData/#/PointingToDeclaration/)|  [JVM] 得到原始数据字符串。 数据不应该为null。abstract override val [originalData](index.md#love.forte.simbot.common.api.message/MsgGet/originalData/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [remark](index.md#love.forte.simbot.common.api.message/MsgGet/remark/#/PointingToDeclaration/)|  [JVM] 好友备注或群名片abstract override val [remark](index.md#love.forte.simbot.common.api.message/MsgGet/remark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [remarkOrNickname](index.md#love.forte.simbot.common.api.message/MsgGet/remarkOrNickname/#/PointingToDeclaration/)|  [JVM] 如果有备注则得到备注，否则得到昵称open override val [remarkOrNickname](index.md#love.forte.simbot.common.api.message/MsgGet/remarkOrNickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [time](index.md#love.forte.simbot.common.api.message/MsgGet/time/#/PointingToDeclaration/)|  [JVM] 消息接收到的时间。一般是一个时间戳。abstract val [time](index.md#love.forte.simbot.common.api.message/MsgGet/time/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [MessageEventGet](../-message-event-get/index.md)
| [MessageRecallEventGet](../-message-recall-event-get/index.md)

