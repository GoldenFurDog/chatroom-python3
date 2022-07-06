# chatroom-python3
基于Python的简易聊天室。版本v1.1.0
遵循CC协议
将文件下载至两台电脑中（注意两台电脑不可用相同的文件，例如电脑A使用server端则电脑B使用client端），运行文件即可进行临时简易通信（基于UDP协议）。
server端需输入本机IP地址，选择开放端口并输入任意用户名，即等待client端连接。
client端需输入与server端用户商定好的IP地址，指定的端口，输入任意用户名，即连接至server端，可以开始通信。
若要停止通信，任意电脑发送"stop"，直接关闭终端或按下Ctrl+C即可退出。
