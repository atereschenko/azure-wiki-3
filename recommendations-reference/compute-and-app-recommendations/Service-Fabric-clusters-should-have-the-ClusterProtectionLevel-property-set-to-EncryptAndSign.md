|Recommendation|Description & related policy|Severity|Quick fix enabled?([Learn more](https://docs.microsoft.com/azure/security-center/security-center-remediate-recommendations#recommendations-with-quick-fix-remediation))|Resource type|
|----|----|----|----|----|
|**Service Fabric clusters should have the ClusterProtectionLevel property set to EncryptAndSign**|Service Fabric provides three levels of protection (None, Sign, and EncryptAndSign) for node-to-node communication using a primary cluster certificate. Set the protection level to ensure that all node-to-node messages are encrypted and digitally signed.<br>(Related policy: The ClusterProtectionLevel property to EncryptAndSign in Service Fabric should be set)|High|N|Compute resources (service fabric)|


