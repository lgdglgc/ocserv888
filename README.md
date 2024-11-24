# ocserv 一键安装脚本
``` bash
curl -O https://raw.githubusercontent.com/lgdglgc/ocserv888/main/ocserv.sh
```
``` bash
bash ocserv.sh
```
``` bash
systemctl restart ocserv
```
``` bash
systemctl stop ocserv
```
``` bash
systemctl status ocserv
```
```bash
ocpasswd -c /etc/ocserv/ocpasswd <用户名>
```
```bash
ocserv -c /etc/ocserv.conf
```
#root@vpn:/etc/ocserv# netstat -tulpn | grep 443
#tcp        0      0 0.0.0.0:443             0.0.0.0:*               LISTEN      1987/ocserv
#tcp6       0      0 :::443                  :::*                    LISTEN      1987/ocserv
#udp        0      0 0.0.0.0:443             0.0.0.0:*                           1987/ocserv
#udp6       0      0 :::443                  :::*                                1987/ocserv
