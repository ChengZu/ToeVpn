# ToeVpn
java 服务器（内存一直增加，希望有人提供帮助），android客户端

# 如何配置服务器（Ubuntu）

1.安装jdk
```  
apt install openjdk-11-jdk-headless
```  
2.运行程序
 
 将build/ToeVpn.jar 拷贝到服务器(用WinSCP), 执行下面命令运行
```  
 java -jar ToeVpn.jar
```  

# 如何安装客户端

1.将build/app-release.apk 拷贝到android手机上安装

2.ip选项填服务器IP地址,其他选项默认即可

3.点击启动
