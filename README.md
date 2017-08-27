# /usr/local/bin/fanctld

```bash
leoxiong at garfield in ~ $ cat /etc/systemd/system/fanctld.service 
[Unit]
Description=MacBook fan control

[Service]
Type=simple
ExecStart=/usr/local/bin/fanctld
leoxiong at garfield in ~ $ sudo systemctl start fanctld
```
