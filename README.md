## Deployment

Repository

* [https://github.com/all4dich/node-exporter-service](https://github.com/all4dich/node-exporter-service)

How to enable node-exporter service

1. Download [https://github.com/all4dich/node-exporter-service](https://github.com/all4dich/node-exporter-service) repository 
2. Edit `node-exporter.service` file and set start.sh / stop.sh file's absolute pathes
3. Copy node-exporter.service into `/etc/systemd/system/` .
4. Run this command

```text
sudo systemctl enable node-exporter
sudo systemctl daemon-reload
```
