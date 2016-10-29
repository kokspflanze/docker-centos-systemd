# Docker Container based on latest Centos with systemd

based on https://github.com/docker-library/docs/tree/master/centos#dockerfile-for-systemd-base-image

# Running Container based on systemd

```
docker run -ti -v /sys/fs/cgroup:/sys/fs/cgroup:ro -p kokspflanze/centos-systemd
```