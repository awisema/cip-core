# Buglog

The buglog records when bugs are discovered along with an estimation of the activity when they were first introduced.

Bug IDs may be machine generated to ensure uniqueness, but should be "human scale" to allow users to easily associate bug and timelog entries.

|Name|Type|Description|Example|
|-|-|-|-|
|bug|ID|An id to link a fault to effort in the timelog|1|
|story|String|Story identifier|`#123456`|
|found|String|Process activity where fault was discovered|`testing`|
|introduced|String|Estimated process activity where fault was introduced|`requirements`|
|description|String|Short description of the fault|`Missing primary key`|
