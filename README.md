# nats-snapcraft

### Build

```sh
$ snapcraft

Skipping pull gnatsd (already ran)
Skipping build gnatsd (already ran)
Skipping stage gnatsd (already ran)
Skipping prime gnatsd (already ran)
Snapping 'nats-server'
Snapped nats-server_0.9.4_amd64.snap
```

### Install

```sh
sudo snap install --force-dangerous nats-server_0.9.4_amd64.snap 
74.87 MB / 74.93 MB  99.93 % 3.20 MB/s 

nats-server 0.9.4 installed
```

### Confirm

```sh
which nats-server

/snap/bin/nats-server
nats-server

[19847] 2016/11/22 10:54:04.530076 [INF] Starting nats-server version 0.9.4
[19847] 2016/11/22 10:54:04.531992 [INF] Listening for client connections on 0.0.0.0:4222
[19847] 2016/11/22 10:54:04.532128 [INF] Server is ready
```
