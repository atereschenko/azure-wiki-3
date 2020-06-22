|Alert|Description|Intent ([Learn more](#intentions))|Severity|
|----|----|:----:|--|
|**Exposed Docker daemon detected**|Machine logs indicate that your Docker daemon (dockerd) exposes a TCP socket. By default, Docker configuration doesn't use encryption or authentication when a TCP socket is enabled. Anyone with access to the relevant port can then get full access to the Docker daemon.|Exploitation / Execution|Medium|


