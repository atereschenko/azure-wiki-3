|Alert|Description|Intent ([Learn more](#intentions))|Severity|
|----|----|:----:|--|
|**New container in the kube-system namespace detected**|Kubernetes audit log analysis detected a new container in the kube-system namespace that isn't among the containers that normally run in this namespace. The kube-system namespaces shouldn't contain user resources. Attackers can use this namespace to hide malicious components.|Persistence|Low|


