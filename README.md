# Simple container running `squid`

```
$ docker run \
    --name squid \
    -v $(pwd)/squid.conf:/etc/squid/squid.conf \
    -p 127.0.0.1:3128:3128/tcp \
    -d gbraad/squid
```

