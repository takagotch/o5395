### serf
---
https://github.com/hashicorp/serf

https://www.serf.io/

```sh
serf agent -node=foo -bind=127.0.0.1:5000 -rpc-addr=127.0.0.1:7373
serf agent -node=bar -bind=127.0.0.1:5001 -rpc-addr=127.0.0.1:7374
serf join 127.0.0.1:5001
serf members

make 
bin/serf
# bin/.bash
make test
```

```
```

```
```


