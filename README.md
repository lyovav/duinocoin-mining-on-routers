opkg update
opkg install python3
opkg install coreutils-nohup
opkg install libustream-openssl
opkg install ca-bundle


nohup python3 /www/miner.py &
