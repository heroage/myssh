# myssh
> 写的第一个 shell 脚本，用来自动化 ssh、telnet 登录  
## 文件说明
* myssh: 主文件，读取 device.txt 内容，并根据用户输入调用 conn.exp 发起远程连接
* conn.exp: 使用 expect 与设备交互
* device.txt: 设备列表，分别为 设备名称、地址、协议(ssh或telnet)
