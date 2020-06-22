|Alert|Description|Intent ([Learn more](#intentions))|Severity|
|----|----|:----:|--|
|**Detected suspicious use of Pcalua.exe to launch executable code**|Analysis of host data on %{Compromised Host} detected the use of pcalua.exe to launch executable code. Pcalua.exe is component of the Microsoft Windows "Program Compatibility Assistant" which detects compatibility issues during the installation or execution of a program. Attackers are known to abuse functionality of legitimate Windows system tools to perform malicious actions, for example using pcalua.exe with the -a switch to launch malicious executables either locally or from remote shares.|-|Medium|


