|Alert|Description|Intent ([Learn more](#intentions))|Severity|
|----|----|:----:|--|
|**Impossible travel activity**|Two user activities (in a single or multiple sessions) have occurred, originating from geographically distant locations. This occurs within a time period shorter than the time it would have taken the user to travel from the first location to the second. This indicates that a different user is using the same credentials.<br>This detection uses a machine learning algorithm that ignores obvious false positives contributing to the impossible travel conditions, such as VPNs and locations regularly used by other users in the organization. The detection has an initial learning period of seven days, during which it learns a new user's activity pattern. |-|Medium|


