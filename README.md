catbox-redis-sentinel
============

This is a fork of catbox-redis.

Redis adapter for catbox

Lead Maintainer: [Eran Hammer](https://github.com/hueniverse)

### Options

- `host` - the Redis server hostname. Defaults to `'127.0.0.1'`.
- `endpoints` - the Redis server endpoints. Defaults to `'127.0.0.1'`.

Example:

`[{'host':'10.0.0.1','port':26379}, {'host':'10.0.0.2','port':26379}]`

- `port` - the Redis server port or unix domain socket path. Defaults to `6379`.
- `password` - the Redis authentication password when required.
- `partition` - this will store items under keys that start with this value. (Default: '')
