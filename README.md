# docker-restart

```
touch docker.sh
```
```
nano docker.sh
```
```
#!/bin/sh
```
```
docker restart
```
```
chmod 755 docker.sh
```
```
apt-get install cron
```
```
crontab -e
```
```
*/1440 * * * * sh /root/docker.sh
```

## Done
