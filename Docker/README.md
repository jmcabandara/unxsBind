## unxsio/unxsbind Docker Container and Docker-Compose service stack.

This project will allow you to very quickly rollout a set of managed authoritative name servers.

We only use ISC BIND DNS named name servers.

### Info/Warning

Just starting out with the this project.
Look at the ```docker-compose.yml``` file for a local Dockerfile based test install.

You will need an SSL nginx-proxy and a mysql server at minimum.

### Roadmap

 * Add Dockerfile for managed NS containers.
 * Add autodiscovery of managed NS via DNS SRV records for mangement container.
 * Add failover management stack with MySQL replication support.
