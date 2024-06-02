# raft-redis-cluster

「Go で作って理解する Raft ベース Redis 互換 KVS」のコード

```sh
make -j 3 run
```

```sh
❯ redis-cli -c -p 63791
localhost:63792> SET key1 value1
OK
localhost:63792>
localhost:63792> GET key1
"value1"
localhost:63792> quit
```
