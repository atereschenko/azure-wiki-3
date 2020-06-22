|Recommendation|Description & related policy|Severity|Quick fix enabled?([Learn more](https://docs.microsoft.com/azure/security-center/security-center-remediate-recommendations#recommendations-with-quick-fix-remediation))|Resource type|
|----|----|----|----|----|
|**All network ports should be restricted on NSG associated to your VM**|Harden the network security groups of your Internet-facing VMs by restricting the access of your existing allow rules.<br>This recommendation is triggered when any port is opened to *all* sources (except for ports 22, 3389, 5985, 5986, 80, and 1443).<br>(Related policy: Access through internet facing endpoint should be restricted)|High|N|Virtual machine|


