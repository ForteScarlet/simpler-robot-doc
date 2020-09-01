//[common-api](../index.md)/[love.forte.simbot.common.api.message](index.md)



# Package love.forte.simbot.common.api.message  


## Types  
  
|  Name|  Summary| 
|---|---|
| [GroupMsg](-group-msg/index.md)| [JVM]  <br>Brief description  <br>群消息  <br>Content  <br>interface [GroupMsg](-group-msg/index.md) : [MessageEventGet](-message-event-get/index.md), [GroupContainer](../love.forte.simbot.common.api.message.containers/-group-container/index.md)  <br><br><br>
| [MessageEventGet](-message-event-get/index.md)| [JVM]  <br>Brief description  <br>与消息有关的事件 除了[MsgGet](-msg-get/index.md)中的东西以外, 还要有一个[FlagContainer](../love.forte.simbot.common.api.message.containers/-flag-container/index.md)。 但是一般来讲, [FlagContainer.flag](../love.forte.simbot.common.api.message.containers/-flag-container/index.md#love.forte.simbot.common.api.message.containers/FlagContainer/flag/#/PointingToDeclaration/) 都可以用 [id](-message-event-get/index.md#love.forte.simbot.common.api.message/MessageEventGet/id/#/PointingToDeclaration/)来代替。 因此 [flag](-message-event-get/index.md#love.forte.simbot.common.api.message/MessageEventGet/flag/#/PointingToDeclaration/)提供为默认方法并使用[id](-message-event-get/index.md#love.forte.simbot.common.api.message/MessageEventGet/id/#/PointingToDeclaration/)作为返回值。如果有特殊需要则重写  <br>Content  <br>interface [MessageEventGet](-message-event-get/index.md) : [MsgGet](-msg-get/index.md), [FlagContainer](../love.forte.simbot.common.api.message.containers/-flag-container/index.md)  <br><br><br>
| [MessageRecallEventGet](-message-recall-event-get/index.md)| [JVM]  <br>Brief description  <br>与消息撤回有关的事件 例如群消息撤回或者私聊撤回 一般来讲应该可以得到撤回的[消息内容](-msg-get/index.md#love.forte.simbot.common.api.message/MsgGet/msg/#/PointingToDeclaration/)以及[撤回时间](-message-recall-event-get/index.md#love.forte.simbot.common.api.message/MessageRecallEventGet/recallTime/#/PointingToDeclaration/)  <br>Content  <br>interface [MessageRecallEventGet](-message-recall-event-get/index.md) : [MsgGet](-msg-get/index.md)  <br><br><br>
| [MsgGet](-msg-get/index.md)| [JVM]  <br>Brief description  <br>监听消息的父接口。所有的监听消息都应当实现的容器：<ul><li>[原始信息容器](../love.forte.simbot.common.api.message.containers/-original-data-container/index.md),</li><li>[bot基础信息容器](../love.forte.simbot.common.api.message.containers/-bot-container/index.md),</li><li>[用户容器](../love.forte.simbot.common.api.message.containers/-account-container/index.md)</li></ul>  <br>Content  <br>interface [MsgGet](-msg-get/index.md) : [OriginalDataContainer](../love.forte.simbot.common.api.message.containers/-original-data-container/index.md), [BotContainer](../love.forte.simbot.common.api.message.containers/-bot-container/index.md), [AccountContainer](../love.forte.simbot.common.api.message.containers/-account-container/index.md)  <br><br><br>
| [PrivateMsg](-private-msg/index.md)| [JVM]  <br>Brief description  <br>私聊消息  <br>Content  <br>interface [PrivateMsg](-private-msg/index.md) : [MessageEventGet](-message-event-get/index.md)  <br><br><br>

