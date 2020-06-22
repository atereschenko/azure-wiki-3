|Alert|Description|Intent ([Learn more](#intentions))|Severity|
|----|----|:----:|--|
|**Fileless attack technique detected**|The memory of the process specified below contains evidence of a fileless attack technique. Fileless attacks are used by attackers to execute code while evading detection by security software. Specific behaviors include:<br>1) Shellcode, which is a small piece of code typically used as the payload in the exploitation of a software vulnerability.<br>2) Executable image injected into the process, such as in a code injection attack.<br>3) Active network connections. See NetworkConnections below for details.<br>4) Function calls to security sensitive operating system interfaces. See Capabilities below for referenced OS capabilities.<br>5) Process hollowing, which is a technique used by malware in which a legitimate process is loaded on the system to act as a container for hostile code.<br>6) Contains a thread that was started in a dynamically allocated code segment. This is a common pattern for process injection attacks.|DefenseEvasion / Execution|High|

