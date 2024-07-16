```shell
sudo systemctl stop sonaricd
apt update
apt upgrade sonaric
sudo systemctl daemon-reload
sudo systemctl restart sonaricd
sudo systemctl status sonaricd
sonaric node-info
```
