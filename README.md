* setup
```
yum install vsftpd ftp
systemctl stop vsftpd.service
```

* location
```
/sbin/vsftpd
```

* start manually
```
/sbin/vsftpd /etc/vsftpd/vsftpd.conf &
ps -ef | grep vsftpd
ftp localhost
killall vsftpd
```

* start and stop daemon using SYSV script
```

```
