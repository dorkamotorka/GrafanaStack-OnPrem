# Requirements

In order to connect to the docker daemon, which is required by the Grafana Agent, you need to create a symlink using:

```
ln -s .docker/run/docker.sock /var/run/docker.sock
```
