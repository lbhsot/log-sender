# log-sender
Aim to monitor log file(such as nginx access.log / error.log) and send the diff to remote server

Usage:

```
log-sender -f /var/log/nginx/access.log --url http://localhost:5000/logs
```
