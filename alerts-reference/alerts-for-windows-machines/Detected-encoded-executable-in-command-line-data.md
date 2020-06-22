|Alert|Description|Intent ([Learn more](#intentions))|Severity|
|----|----|:----:|--|
|**Detected encoded executable in command line data**|Analysis of host data on %{Compromised Host} detected a base-64 encoded executable. This has previously been associated with attackers attempting to construct executables on-the-fly through a sequence of commands, and attempting to evade intrusion detection systems by ensuring that no individual command would trigger an alert. This could be legitimate activity, or an indication of a compromised host.|-|High|


