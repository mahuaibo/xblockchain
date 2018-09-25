**Qtumd启动**

qtumd 

**Docker启动**

```
#! /bin/bash
docker run -d --name qtum_mainnet \
    -e "QTUM\_NETWORK=mainnet" \
    -e "QTUM\_RPC\_USER=qtum" \
    -e "QTUM\_RPC\_PASS=mainnet" \
    -v ${PWD}:/dapp \
    -p 13889:3889 \
    hayeah/qtumportal:latest
```



