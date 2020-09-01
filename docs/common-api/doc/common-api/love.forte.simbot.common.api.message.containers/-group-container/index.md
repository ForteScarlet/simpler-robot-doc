//[common-api](../../index.md)/[love.forte.simbot.common.api.message.containers](../index.md)/[GroupContainer](index.md)



# GroupContainer  
 [JVM] 群信息容器，实现 [群头像容器](../-group-avatar-container/index.md)[群账号容器](../-group-code-container/index.md)[群名称容器](../-group-name-container/index.md)  
  
interface [GroupContainer](index.md) : [GroupAvatarContainer](../-group-avatar-container/index.md), [GroupCodeContainer](../-group-code-container/index.md), [GroupNameContainer](../-group-name-container/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)| [JVM]  <br>Content  <br>open operator override fun [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)| [JVM]  <br>Content  <br>open override fun [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)| [JVM]  <br>Content  <br>open override fun [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [groupAvatar](index.md#love.forte.simbot.common.api.message.containers/GroupContainer/groupAvatar/#/PointingToDeclaration/)|  [JVM] 群头像. 一般来讲为null的可能性很小abstract override val [groupAvatar](index.md#love.forte.simbot.common.api.message.containers/GroupContainer/groupAvatar/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [groupCode](index.md#love.forte.simbot.common.api.message.containers/GroupContainer/groupCode/#/PointingToDeclaration/)|  [JVM] 群号abstract override val [groupCode](index.md#love.forte.simbot.common.api.message.containers/GroupContainer/groupCode/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [groupCodeNumber](index.md#love.forte.simbot.common.api.message.containers/GroupContainer/groupCodeNumber/#/PointingToDeclaration/)|  [JVM] 群号的[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)类型。如果可以作为数字的话。open override val [groupCodeNumber](index.md#love.forte.simbot.common.api.message.containers/GroupContainer/groupCodeNumber/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [groupName](index.md#love.forte.simbot.common.api.message.containers/GroupContainer/groupName/#/PointingToDeclaration/)|  [JVM] 群名称abstract override val [groupName](index.md#love.forte.simbot.common.api.message.containers/GroupContainer/groupName/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [GroupMsg](../../love.forte.simbot.common.api.message/-group-msg/index.md)

