# pm2-guarded

## How to use

```bash
$ pm2 install pm2-guarded
```

### Send to influxdb

```bash
$ pm2 set pm2-guarded:influxdb http://user:pass@host:port/db
```

### Config

- set info fetch interval `pm2 set pm2-guarded:fetchInterval 1000`
- set data send interval `pm2 set pm2-guarded:sendInterval 5000`
