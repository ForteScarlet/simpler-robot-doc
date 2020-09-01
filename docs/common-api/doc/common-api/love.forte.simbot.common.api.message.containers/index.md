//[common-api](../index.md)/[love.forte.simbot.common.api.message.containers](index.md)



# Package love.forte.simbot.common.api.message.containers  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AccountAvatarContainer](-account-avatar-container/index.md)| [JVM]  <br>Brief description  <br>账户头像容器，定义可以得到一个头像链接。 头像不是必须的，可能会不存在。  <br>Content  <br>interface [AccountAvatarContainer](-account-avatar-container/index.md)  <br><br><br>
| [AccountCodeContainer](-account-code-container/index.md)| [JVM]  <br>Brief description  <br>账户号码容器。定义可以得到一个账号的号码 其中,[codeNumber](-account-code-container/index.md#love.forte.simbot.common.api.message.containers/AccountCodeContainer/codeNumber/#/PointingToDeclaration/)默认为[code](-account-code-container/index.md#love.forte.simbot.common.api.message.containers/AccountCodeContainer/code/#/PointingToDeclaration/).[toLong](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/index.html)  <br>Content  <br>interface [AccountCodeContainer](-account-code-container/index.md)  <br><br><br>
| [AccountContainer](-account-container/index.md)| [JVM]  <br>Brief description  <br>一个账号信息容器, 继承了 [用户名称容器](-account-name-container/index.md)[用户头像容器](-account-avatar-container/index.md)[用户账号容器](-account-code-container/index.md)  <br>Content  <br>interface [AccountContainer](-account-container/index.md) : [AccountNameContainer](-account-name-container/index.md), [AccountAvatarContainer](-account-avatar-container/index.md), [AccountCodeContainer](-account-code-container/index.md)  <br><br><br>
| [AccountNameContainer](-account-name-container/index.md)| [JVM]  <br>Brief description  <br>账户名称容器，即 [账号昵称容器](-account-nickname-container/index.md) 与 [账号备注容器](-account-remark-container/index.md) 并提供几个默认的整合值:<ul><li>[备注或昵称](-account-name-container/index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/remarkOrNickname/#/PointingToDeclaration/)</li><li>[昵称与备注](-account-name-container/index.md#love.forte.simbot.common.api.message.containers/AccountNameContainer/nicknameAndRemark/#/PointingToDeclaration/)</li></ul>  <br>Content  <br>interface [AccountNameContainer](-account-name-container/index.md) : [AccountNicknameContainer](-account-nickname-container/index.md), [AccountRemarkContainer](-account-remark-container/index.md)  <br><br><br>
| [AccountNicknameContainer](-account-nickname-container/index.md)| [JVM]  <br>Brief description  <br>账户昵称容器。定义可以得到一个账号的昵称 昵称可能不存在。  <br>Content  <br>interface [AccountNicknameContainer](-account-nickname-container/index.md)  <br><br><br>
| [AccountRemarkContainer](-account-remark-container/index.md)| [JVM]  <br>Brief description  <br>账户备注容器。定义可以得到一个账号的备注信息。可能是好友备注或者群名片。 备注可能不存在  <br>Content  <br>interface [AccountRemarkContainer](-account-remark-container/index.md)  <br><br><br>
| [BotAvatarContainer](-bot-avatar-container/index.md)| [JVM]  <br>Brief description  <br>机器人自身的头像容器 头像不是必须的，可能不存在  <br>Content  <br>interface [BotAvatarContainer](-bot-avatar-container/index.md)  <br><br><br>
| [BotCodeContainer](-bot-code-container/index.md)| [JVM]  <br>Brief description  <br>机器人自身的账号容器  <br>Content  <br>interface [BotCodeContainer](-bot-code-container/index.md)  <br><br><br>
| [BotContainer](-bot-container/index.md)| [JVM]  <br>Brief description  <br>机器人基础信息容器, 其实现了 [机器人账号容器](-bot-code-container/index.md)[机器人名称容器](-bot-name-container/index.md)[机器人头像容器](-bot-avatar-container/index.md)  <br>Content  <br>interface [BotContainer](-bot-container/index.md) : [BotCodeContainer](-bot-code-container/index.md), [BotNameContainer](-bot-name-container/index.md), [BotAvatarContainer](-bot-avatar-container/index.md)  <br><br><br>
| [BotNameContainer](-bot-name-container/index.md)| [JVM]  <br>Brief description  <br>机器人自身的名称容器  <br>Content  <br>interface [BotNameContainer](-bot-name-container/index.md)  <br><br><br>
| [FlagContainer](-flag-container/index.md)| [JVM]  <br>Brief description  <br>标识容器。定义可以得到一个字符串标识。 但是一般来讲, [MsgGet]([MsgGet])的[FlagContainer](-flag-container/index.md)实现容器基本上都可以通过[MsgGet.id]([MsgGet.id])来实现  <br>Content  <br>interface [FlagContainer](-flag-container/index.md)  <br><br><br>
| [GroupAvatarContainer](-group-avatar-container/index.md)| [JVM]  <br>Brief description  <br>群头像容器。定义可以得到群头像 头像不是必须的，可能会不存在  <br>Content  <br>interface [GroupAvatarContainer](-group-avatar-container/index.md)  <br><br><br>
| [GroupCodeContainer](-group-code-container/index.md)| [JVM]  <br>Brief description  <br>群号容器。定义可以得到一个群的群号  <br>Content  <br>interface [GroupCodeContainer](-group-code-container/index.md)  <br><br><br>
| [GroupContainer](-group-container/index.md)| [JVM]  <br>Brief description  <br>群信息容器，实现 [群头像容器](-group-avatar-container/index.md)[群账号容器](-group-code-container/index.md)[群名称容器](-group-name-container/index.md)  <br>Content  <br>interface [GroupContainer](-group-container/index.md) : [GroupAvatarContainer](-group-avatar-container/index.md), [GroupCodeContainer](-group-code-container/index.md), [GroupNameContainer](-group-name-container/index.md)  <br><br><br>
| [GroupNameContainer](-group-name-container/index.md)| [JVM]  <br>Brief description  <br>群名称容器，定义可以得到群的群名称  <br>Content  <br>interface [GroupNameContainer](-group-name-container/index.md)  <br><br><br>
| [OriginalDataContainer](-original-data-container/index.md)| [JVM]  <br>Brief description  <br>原始数据容器。 定义可以得到原始数据的字符串信息。  <br>Content  <br>interface [OriginalDataContainer](-original-data-container/index.md)  <br><br><br>

