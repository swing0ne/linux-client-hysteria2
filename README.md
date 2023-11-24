# linux-client-hysteria2
在linux系统下运行hysteria2代理
1、拥有一台vps并且配置好hysteria2服务端  
**一键安装脚本**
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/Misaka-blog/hysteria-install/main/hy2/hysteria.sh && bash hysteria.sh
```
2、导出客户端配置文件（yaml）并在linux上下载[hysteria内核](https://github.com/apernet/hysteria/releases)  
3、给可执行文件添加执行权限
```shell  
sudo chmod +x "可执行文件名称"
```
4、  
```shell
./"可执行文件名称"
```
5、firefox上下载proxy swichyomega  
6、proxy配置中填写代理地址127.0.0.1:端口号  
7、挂到后台  
```shell
nohup ./"可执行文件名称" &
```
