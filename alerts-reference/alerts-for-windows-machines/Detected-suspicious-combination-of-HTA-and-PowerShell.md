|Alert|Description|Intent ([Learn more](#intentions))|Severity|
|----|----|:----:|--|
|**Detected suspicious combination of HTA and PowerShell**|mshta.exe (Microsoft HTML Application Host) which is a signed Microsoft binary is being used by the attackers to launch malicious PowerShell commands.  Attackers often resort to having an HTA file with inline VBScript.  When a victim browses to the HTA file and chooses to run it, the PowerShell commands and scripts that it contains are executed. Analysis of host data on %{Compromised Host} detected mshta.exe launching PowerShell commands.|-|Medium|


