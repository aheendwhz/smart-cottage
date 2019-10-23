# Smart cottage

TIG stack for smart home component monitoring & visualisation on a Raspberry Pi 4 micro-server. Minimal bootstrapped config and low retention with Docker :whale: to allow quick and dirty spin-up/tear-down. 

## Get started

```bash
docker-compose up
```

## TODO
- [x] set up volumes and research storage with Docker
- [x] volume for grafana to persist data
- [ ] set up volume(s) for influxdb
- [ ] see https://github.com/nicolargo/docker-influxdb-grafana/blob/master/docker-compose.yml for help
- [ ] get grafana and influxdb communicating
- [ ] eventually, make Dockerfiles for all services, e.g. have a grafana dashboard json config copied in during image build, etc.
- [ ] allow editing via vscode over SSH
- [ ] test getting data into influx with telegraf
- [x] https://github.com/grafana/grafana/issues/19585

