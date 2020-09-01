//[common-api](../../index.md)/[love.forte.simbot.common.api.message](../index.md)/[MessageRecallEventGet](index.md)



# MessageRecallEventGet  
 [JVM] 与消息撤回有关的事件 例如群消息撤回或者私聊撤回 一般来讲应该可以得到撤回的[消息内容](../-msg-get/index.md#love.forte.simbot.common.api.message/MsgGet/msg/#/PointingToDeclaration/)以及[撤回时间](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/recallTime/#/PointingToDeclaration/)  
  
interface [MessageRecallEventGet](index.md) : [MsgGet](../-msg-get/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)| [JVM]  <br>Content  <br>open operator override fun [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)| [JVM]  <br>Content  <br>open override fun [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../-msg-get/to-string.md)| [JVM]  <br>Brief description  <br>应当重写toString方法  <br>Content  <br>abstract override fun [toString](../-msg-get/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [avatar](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/avatar/#/PointingToDeclaration/)|  [JVM] 得到账号的头像地址. 一般来讲为null的可能性很小abstract override val [avatar](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/avatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [botAvatar](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/botAvatar/#/PointingToDeclaration/)|  [JVM] 机器人的头像abstract override val [botAvatar](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/botAvatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [botCode](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/botCode/#/PointingToDeclaration/)|  [JVM] 当前的bot的账号abstract override val [botCode](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/botCode/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [botCodeNumber](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/botCodeNumber/#/PointingToDeclaration/)|  [JVM] 得到[botCode](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/botCode/#/PointingToDeclaration/)的[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)类型。如果可以作为数字的话。open override val [botCodeNumber](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/botCodeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [botName](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/botName/#/PointingToDeclaration/)|  [JVM] 机器人的名称abstract override val [botName](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/botName/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [code](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/code/#/PointingToDeclaration/)|  [JVM] 账号abstract override val [code](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/code/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [codeNumber](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/codeNumber/#/PointingToDeclaration/)|  [JVM] 账号的数字值。（如果能作为数字的话）open override val [codeNumber](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/codeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [id](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/id/#/PointingToDeclaration/)|  [JVM] 当前监听事件消息的ID。一般情况下应当是一个唯一ID。abstract override val [id](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [msg](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/msg/#/PointingToDeclaration/)|  [JVM] 监听消息的消息正文文本abstract override var [msg](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/msg/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [nickname](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/nickname/#/PointingToDeclaration/)|  [JVM] 昵称abstract override val [nickname](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/nickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [nicknameAndRemark](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/nicknameAndRemark/#/PointingToDeclaration/)|  [JVM] 昵称与备注, 返回一个账号(备注)?格式的字符串. 例如：<ul><li>张三(张三的备注)</li><li>李四 (没有备注)</li></ul>open override val [nicknameAndRemark](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/nicknameAndRemark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [originalData](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/originalData/#/PointingToDeclaration/)|  [JVM] 得到原始数据字符串。 数据不应该为null。abstract override val [originalData](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/originalData/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [recallTime](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/recallTime/#/PointingToDeclaration/)|  [JVM] 撤回时间。 使用[LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)来代表一个准确时间点以防止使用事件戳导致时间格式不统一abstract val [recallTime](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/recallTime/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)   <br>
| [remark](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/remark/#/PointingToDeclaration/)|  [JVM] 好友备注或群名片abstract override val [remark](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/remark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [remarkOrNickname](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/remarkOrNickname/#/PointingToDeclaration/)|  [JVM] 如果有备注则得到备注，否则得到昵称open override val [remarkOrNickname](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/remarkOrNickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [time](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/time/#/PointingToDeclaration/)|  [JVM] 消息接收到的时间。一般是一个时间戳。abstract override val [time](index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/time/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>

