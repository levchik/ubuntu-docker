# ubuntu-docker
Ubuntu 14.04 with Docker in it. Support for host TCP connections.

- Private network enabled on 192.168.33.10 by default.
- Port forwarding is enabled on 2375 port, which is the port docker daemon is listening to inside VM.
- Connect with any docker client to this URI: tcp://192.168.33.10:2375
