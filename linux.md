# Linux notes

## What holds a port

```bash
lsof -i :8080
ss -tulpn | grep 8080
```

## Disk usage

```bash
du -sh * | sort -h
df -h
```

## Processes

```bash
ps aux --sort=-%mem | head
journalctl -u svc -f
```
