# Smart cottage

TIG stack for smart home component monitoring & visualisation on a Raspberry Pi 4 micro-server. Minimal bootstrapped config and low retention with Docker :whale: to allow quick and dirty spin-up/tear-down. 

## Get started

```bash
docker-compose up
```

## TODO
- [ ] set up volumes and research storage with Docker
 - [ ] busybox? set up another service for storage
- [ ] get grafana and influxdb communicating
- [ ] allow editing via vscode over SSH
- [ ] test getting data into influx wit telegraf
- [ ] https://github.com/grafana/grafana/issues/19585

