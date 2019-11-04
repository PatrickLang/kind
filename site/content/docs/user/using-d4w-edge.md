
## Prerequisites


- **Docker Desktop Community 2.1.5.0** or later - see [Docker Desktop for Windows Edge]
- Windows 10 Insider build 18990 or later - see [Getting Windows 10 Insider Preview](/docs/user/using-wsl2#Getting-Windows-10-Insider-Preview)
- Support for Intel VT or AMD-V instructions, on hardware and from the hypervisor if you are running Windows in a VM

## Running Kind



## Merging kubeconfig


## Building from source


## Using a newer kubectl

> TODO - Docker puts a shipped version in PATH

```
get-command kubectl

CommandType     Name                                               Version    Source
-----------     ----                                               -------    ------
Application     kubectl.exe                                        0.0.0.0    C:\Program Files\Docker\Docker\resources\bin\kubectl.exe


PS C:\Users\plang> kubectl version
Client Version: version.Info{Major:"1", Minor:"15", GitVersion:"v1.15.5", GitCommit:"20c265fef0741dd71a66480e35bd69f18351daea", GitTreeState:"clean", BuildDate:"2019-10-15T19:16:51Z", GoVersion:"go1.12.10", Compiler:"gc", Platform:"windows/amd64"}
Server Version: version.Info{Major:"1", Minor:"15", GitVersion:"v1.15.5", GitCommit:"20c265fef0741dd71a66480e35bd69f18351daea", GitTreeState:"clean", BuildDate:"2019-10-15T19:07:57Z", GoVersion:"go1.12.10", Compiler:"gc", Platform:"linux/amd64"}
```


[Docker Desktop for Windows Edge]: https://docs.docker.com/docker-for-windows/edge-release-notes/