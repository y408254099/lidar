# lidar
### 设置静态 IP

创建配置文件 `/etc/systemd/network/20-wired.network`：

```
[Match]
Name=eth0

[Network]
Address=192.168.0.157/24
Gateway=192.168.0.1
DNS=192.168.0.1
