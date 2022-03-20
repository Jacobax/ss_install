# ss_install
ss简易搭建  
snap安装ss-libev  
```snap install shadowsocks-libev --edge```  
编辑配置  
```nano /var/snap/shadowsocks-libev/common/etc/shadowsocks-libev/config.json```  
启动ss  
```systemctl start snap.shadowsocks-libev.ss-server-daemon.service```  
开机自启  
```systemctl enable snap.shadowsocks-libev.ss-server-daemon.service```  
