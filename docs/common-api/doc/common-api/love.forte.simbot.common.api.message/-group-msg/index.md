//[common-api](../../index.md)/[love.forte.simbot.common.api.message](../index.md)/[GroupMsg](index.md)



# GroupMsg  
 [JVM] 群消息  
  
interface [GroupMsg](index.md) : [MessageEventGet](../-message-event-get/index.md), [GroupContainer](../../love.forte.simbot.common.api.message.containers/-group-container/index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Type](-type/index.md)| [JVM]  <br>Brief description  <br>群消息类型  <br>Content  <br>enum [Type](-type/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)| [JVM]  <br>Content  <br>open operator override fun [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)| [JVM]  <br>Content  <br>open override fun [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../-msg-get/to-string.md)| [JVM]  <br>Content  <br>abstract override fun [toString](../-msg-get/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [avatar](index.md#love.forte.simbot.common.api.message/GroupMsg/avatar/#/PointingToDeclaration/)|  [JVM] 得到账号的头像地址. 一般来讲为null的可能性很小abstract override val [avatar](index.md#love.forte.simbot.common.api.message/GroupMsg/avatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [botAvatar](index.md#love.forte.simbot.common.api.message/GroupMsg/botAvatar/#/PointingToDeclaration/)|  [JVM] 机器人的头像abstract override val [botAvatar](index.md#love.forte.simbot.common.api.message/GroupMsg/botAvatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [botCode](index.md#love.forte.simbot.common.api.message/GroupMsg/botCode/#/PointingToDeclaration/)|  [JVM] 当前的bot的账号abstract override val [botCode](index.md#love.forte.simbot.common.api.message/GroupMsg/botCode/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [botCodeNumber](index.md#love.forte.simbot.common.api.message/GroupMsg/botCodeNumber/#/PointingToDeclaration/)|  [JVM] 得到[botCode](index.md#love.forte.simbot.common.api.message/GroupMsg/botCode/#/PointingToDeclaration/)的[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)类型。如果可以作为数字的话。open override val [botCodeNumber](index.md#love.forte.simbot.common.api.message/GroupMsg/botCodeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [botName](index.md#love.forte.simbot.common.api.message/GroupMsg/botName/#/PointingToDeclaration/)|  [JVM] 机器人的名称abstract override val [botName](index.md#love.forte.simbot.common.api.message/GroupMsg/botName/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [code](index.md#love.forte.simbot.common.api.message/GroupMsg/code/#/PointingToDeclaration/)|  [JVM] 账号abstract override val [code](index.md#love.forte.simbot.common.api.message/GroupMsg/code/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [codeNumber](index.md#love.forte.simbot.common.api.message/GroupMsg/codeNumber/#/PointingToDeclaration/)|  [JVM] 账号的数字值。（如果能作为数字的话）open override val [codeNumber](index.md#love.forte.simbot.common.api.message/GroupMsg/codeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [flag](index.md#love.forte.simbot.common.api.message/GroupMsg/flag/#/PointingToDeclaration/)|  [JVM] flag标识，一般可用于撤回之类的。默认为ID的值。open override val [flag](index.md#love.forte.simbot.common.api.message/GroupMsg/flag/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [groupAvatar](index.md#love.forte.simbot.common.api.message/GroupMsg/groupAvatar/#/PointingToDeclaration/)|  [JVM] 群头像. 一般来讲为null的可能性很小abstract override val [groupAvatar](index.md#love.forte.simbot.common.api.message/GroupMsg/groupAvatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [groupCode](index.md#love.forte.simbot.common.api.message/GroupMsg/groupCode/#/PointingToDeclaration/)|  [JVM] 群号abstract override val [groupCode](index.md#love.forte.simbot.common.api.message/GroupMsg/groupCode/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [groupCodeNumber](index.md#love.forte.simbot.common.api.message/GroupMsg/groupCodeNumber/#/PointingToDeclaration/)|  [JVM] 群号的[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)类型。如果可以作为数字的话。open override val [groupCodeNumber](index.md#love.forte.simbot.common.api.message/GroupMsg/groupCodeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [groupName](index.md#love.forte.simbot.common.api.message/GroupMsg/groupName/#/PointingToDeclaration/)|  [JVM] 群名称abstract override val [groupName](index.md#love.forte.simbot.common.api.message/GroupMsg/groupName/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [id](index.md#love.forte.simbot.common.api.message/GroupMsg/id/#/PointingToDeclaration/)|  [JVM] 当前监听事件消息的ID。一般情况下应当是一个唯一ID。abstract override val [id](index.md#love.forte.simbot.common.api.message/GroupMsg/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [msg](index.md#love.forte.simbot.common.api.message/GroupMsg/msg/#/PointingToDeclaration/)|  [JVM] 监听消息的消息正文文本abstract override var [msg](index.md#love.forte.simbot.common.api.message/GroupMsg/msg/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [nickname](index.md#love.forte.simbot.common.api.message/GroupMsg/nickname/#/PointingToDeclaration/)|  [JVM] 昵称abstract override val [nickname](index.md#love.forte.simbot.common.api.message/GroupMsg/nickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [nicknameAndRemark](index.md#love.forte.simbot.common.api.message/GroupMsg/nicknameAndRemark/#/PointingToDeclaration/)|  [JVM] 昵称与备注, 返回一个账号(备注)?格式的字符串. 例如：<ul><li>张三(张三的备注)</li><li>李四 (没有备注)</li></ul>open override val [nicknameAndRemark](index.md#love.forte.simbot.common.api.message/GroupMsg/nicknameAndRemark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [originalData](index.md#love.forte.simbot.common.api.message/GroupMsg/originalData/#/PointingToDeclaration/)|  [JVM] 得到原始数据字符串。 数据不应该为null。abstract override val [originalData](index.md#love.forte.simbot.common.api.message/GroupMsg/originalData/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [remark](index.md#love.forte.simbot.common.api.message/GroupMsg/remark/#/PointingToDeclaration/)|  [JVM] 好友备注或群名片abstract override val [remark](index.md#love.forte.simbot.common.api.message/GroupMsg/remark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [remarkOrNickname](index.md#love.forte.simbot.common.api.message/GroupMsg/remarkOrNickname/#/PointingToDeclaration/)|  [JVM] 如果有备注则得到备注，否则得到昵称open override val [remarkOrNickname](index.md#love.forte.simbot.common.api.message/GroupMsg/remarkOrNickname/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [time](index.md#love.forte.simbot.common.api.message/GroupMsg/time/#/PointingToDeclaration/)|  [JVM] 消息接收到的时间。一般是一个时间戳。abstract override val [time](index.md#love.forte.simbot.common.api.message/GroupMsg/time/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [type](index.md#love.forte.simbot.common.api.message/GroupMsg/type/#/PointingToDeclaration/)|  [JVM] 获取消息类型abstract val [type](index.md#love.forte.simbot.common.api.message/GroupMsg/type/#/PointingToDeclaration/): [GroupMsg.Type](-type/index.md)   <br>

