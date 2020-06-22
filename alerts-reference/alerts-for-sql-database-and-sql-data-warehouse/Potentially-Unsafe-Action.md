|Alert|Description|Intent ([Learn more](#intentions))|Severity|
|----|----|:----:|--|
|**Potentially Unsafe Action**|High privileged SQL command which is commonly used in malicious sessions has been executed in an SQL Server. Those commands are recommended to be disabled by default. In some cases, the alert detects a legitimate action (admin script running). In other cases, the alert detects a malicious action (attacker using SQL trusts to breach Windows layer).|Execution|High|


