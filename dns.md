## MacOS清空DNS缓存
```bash
sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder
```
