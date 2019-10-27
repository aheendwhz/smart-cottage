# Smart cottage

TIG stack for smart home component monitoring & visualisation on a Raspberry Pi 4 micro-server. Minimal bootstrapped config and low retention with Docker :whale: to allow quick and dirty spin-up/tear-down. 

## Get started

```bash
docker-compose up
```

## TODO
- [x] set up volumes and research storage with Docker
- [x] volume for grafana to persist data
- [x] set up volume(s) for influxdb
- [x] see https://github.com/nicolargo/docker-influxdb-grafana/blob/master/docker-compose.yml for help
- [x] get grafana and influxdb communicating
- [x] eventually, make Dockerfiles for all services, e.g. have a grafana dashboard json config copied in during image build, etc.
- [ ] allow editing via vscode over SSH
- [x] test getting data into influx with telegraf
- [x] https://github.com/grafana/grafana/issues/19585
- [ ] check retention policy, is autogen ok?
- [ ] create more dashboard widgets, research commonly-used queries/visualisations
- [ ] check best way to store data, do volumes need to be reconfigured?
- [ ] what is best practice for persistence of grafana and influxdb data?
- [ ] see what other interesting stuff we can monitor on the Pi
- [ ] what other weird stuff can we monitor/visualise from public APIs via influxdb HTTP interface?
- [ ] dip toe into MQTT input for telegraf
- [ ] telegraf should probably be on the host and not just monitoring one docker container... :flushed:
- [ ] unrelated but also work out how to get zsh working on Pi and over SSH :computer:
