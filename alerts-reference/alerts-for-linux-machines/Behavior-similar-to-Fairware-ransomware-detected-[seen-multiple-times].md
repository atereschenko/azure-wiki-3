|Alert|Description|Intent ([Learn more](#intentions))|Severity|
|----|----|:----:|--|
|**Behavior similar to Fairware ransomware detected [seen multiple times]**|Analysis of host data on %{Compromised Host} detected the execution of rm -rf commands applied to suspicious locations. As rm -rf will recursively delete files, it is normally used on discrete folders. In this case, it is being used in a location that could remove a lot of data. Fairware ransomware is known to execute rm -rf commands in this folder. This behavior was seen [x] times today on the following machines: [Machine names]|-|Medium|


