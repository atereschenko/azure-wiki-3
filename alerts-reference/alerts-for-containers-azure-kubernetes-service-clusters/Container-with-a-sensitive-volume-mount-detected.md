|Alert|Description|Intent ([Learn more](#intentions))|Severity|
|----|----|:----:|--|
|**Container with a sensitive volume mount detected**|Kubernetes audit log analysis detected a new container with a sensitive volume mount. The volume that was detected is a hostPath type that mounts a sensitive file or folder from the node to the container. If the container gets compromised, the attacker can use this mount to gain access to the node.|PrivilegeEscalation|Medium|


