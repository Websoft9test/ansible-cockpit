# 服务启停

使用由Websoft9提供的 Cockpit 部署方案，可能需要用到的服务如下：

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
systemctl start redis
systemctl stop redis
systemctl restart redis
systemctl status redis
```
