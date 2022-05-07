# Archipelago

Archipelago is a distributed cache. This is work in progress, and is subject to many changes. It is inspired by Netflix' [EVCache](https://github.com/Netflix/EVCache).

Some early thoughts:

- Use memcached as the data layer (or pluggable?)
- Use memcached protocol.
- Use consistent hashing to route requests.
- Add replication. Probably eventually consistent.
- Add data redistribution when scaling up or down: Cache warmup and replication quorum.
- Gossip between nodes?

