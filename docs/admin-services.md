# Start or Stop the Services

These commands you must know when you using the Cockpit of Websoft9

### Cockpit

```shell
sudo systemctl start cockpit-server
sudo systemctl stop cockpit-server
sudo systemctl restart cockpit-server
sudo systemctl status cockpit-server

# you can use this debug mode if Cockpit service can't run
cockpit-server console
```

### MySQL

```shell
sudo systemctl start mysql
sudo systemctl stop mysql
sudo systemctl restart mysql
sudo systemctl status mysql
```

### Redis

```shell
sudo systemctl start redis
sudo systemctl stop redis
sudo systemctl restart redis
sudo systemctl status redis
```
