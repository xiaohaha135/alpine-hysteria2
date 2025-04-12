# alpine-hysteria2
在alpine中安装hysteria2

## 一键食用
```
wget -O hy2.sh https://raw.githubusercontent.com/xiaohaha135/alpine-hysteria2/main/hy2.sh  && sh hy2.sh
```
重复执行，会覆盖密码。  

## 说明：  
配置文件：/etc/hysteria/config.yaml  
使用自签名证书，默认端口38555，安全tls，SNI为： bing.com  
随系统自启动  
看状态 service hysteria status  
重启 service hysteria restart  

## 测试环境：  alpine 3.19.1  

## hy2官方：  
https://github.com/apernet/hysteria  

## xx工具中配置实例：  
<div align=center> <img src="image.png" width = 50%/> </div>




