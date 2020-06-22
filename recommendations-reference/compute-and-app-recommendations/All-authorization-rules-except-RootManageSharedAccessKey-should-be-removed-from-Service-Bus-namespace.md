|Recommendation|Description & related policy|Severity|Quick fix enabled?([Learn more](https://docs.microsoft.com/azure/security-center/security-center-remediate-recommendations#recommendations-with-quick-fix-remediation))|Resource type|
|----|----|----|----|----|
|**All authorization rules except RootManageSharedAccessKey should be removed from Service Bus namespace**|Service Bus clients should not use a namespace level access policy that provides access to all queues and topics in a namespace. To align with the least privilege security model, you should create access policies at the entity level for queues and topics to provide access to only the specific entity.<br>(Related policy: All authorization rules except RootManageSharedAccessKey should be removed from Service Bus namespace)|Low|N|Compute resources (service bus)|


