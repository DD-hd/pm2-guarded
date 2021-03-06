# pm2-guarded

## How to use

```bash
$ pm2 install pm2-guarded
```

### Upgrade

```bash
$ pm2 module:update pm2-guarded
```

### Send to influxdb

```bash
$ pm2 set pm2-guarded:influxdb http://user:pass@host:port/db
```

### Add Nginx status

```bash
$ pm2 set pm2-guarded:nginx http://127.0.0.1/nginx_status
```

### Add Proxy to influxdb

```bash
$ pm2 set pm2-guarded:socketPath /tmp/pm2-guarded.sock
```

### Config

- set info fetch interval `pm2 set pm2-guarded:fetchInterval 1000`
- set data send interval `pm2 set pm2-guarded:sendInterval 5000`
