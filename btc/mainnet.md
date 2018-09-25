**Bitcoind启动**

nohup bitcoind -datadir=/root/btc -daemon=0 -printtoconsole -dbcache=1000 -maxmempool=500 -maxconnections=50 -disablewallet -server -rest -rpcbind=127.0.0.1 -rpcuser=bitcoin -rpcpassword=bitcoin -rpcallowip=127.0.0.1 -rpcport=8332 &

