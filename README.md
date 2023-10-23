# Requirements

In order to connect to the docker daemon, which is required by the Grafana Agent, you need to create a symlink using:
```
ln -s .docker/run/docker.sock /var/run/docker.sock
```

Also until Loki stores its data on the `filesystem`, the following directories need to be created beforehand:
```
mkdir /tmp/loki/data
mkdir /tmp/loki/wal
```
