# dns-flush

Clear the Systemd Resolved DNS cache:
```bash
sudo systemd-resolve --flush-caches
```

for macOS:
```bash
sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder
```
