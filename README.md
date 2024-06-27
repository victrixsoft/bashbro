# bashbro
A Bash-based web file browser - allowing you to remotely browse, stream, view documents and save files via your web browser.  

![Bashbro Usage](assets/bashbro_usage.png)
```
To start bashbro locally on port 5555: 
$> bashbro -s -p 5555
   -or- (condensed syntax)
$> bashbro -sp5555

To start bashbro on a remote server:

 1. Copy bashbro to the remote server
    E.g. scp bashbro <youruser>@<server name/ip>:

 2. Run bashbro
    E.g. ssh <youruser>@<server name/ip> ./bashbro -s -p=<port>

(Open a browser to <server name/ip>:<port>)

```
![Bashbro Demo](assets/bashbro_demo.gif)

You can also download bashbro directly: 

`curl -S https://raw.githubusercontent.com/victrixsoft/bashbro/main/bashbro > bashbro && chmod +x bashbro && ./bashbro -s -p=6556`

`wget -o bashbro https://raw.githubusercontent.com/victrixsoft/bashbro/main/bashbro && chmod +x bashbro && ./bashbro -s -p=6556`

> [!TIP]
> *When using Chrome browser localhost may be blocked, in that case you can use your ip for instance 
> 192.168.1.55:8880 - no tickets on this plz, it's a Windows/Chrome thing.*

[![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=fff)](#)
![Tree version 1.6+](https://img.shields.io/badge/Tree-v1.6+-green)
![Sed](https://img.shields.io/badge/Sed--orange)
![Socat](https://img.shields.io/badge/Socat--blue)
![GNU Getopt](https://img.shields.io/badge/getopt-T=4-yellow)
