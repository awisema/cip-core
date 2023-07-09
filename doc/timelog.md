# Timelog

The timelog records the time, and interruptions, of the activities of processes. The timelog allows for the longitudinal analysis of the effort across various stages in multiple projects.

A timelog record may include a reference to a bug to record the effort to fix it within the context of a stage.

|Name|Required|Type|Description|Example|
|-|-|-|-|-|
|story|Y|String|Story identifier|`#12356`|
|activity|Y|String|Process activity|`requirements`|
|event|Y|String|One of `start`, `stop`|`start`|
|time|Y|Timestamp|Start time|`2023-02-09T20:48`|
|bug||ID|Id to link effort to a bug||
|reason||String|Stop reason|`Finished`|
