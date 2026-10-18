# Networking notes

## TCP handshake

1. SYN
2. SYN-ACK
3. ACK

## Teardown

Four-way: FIN, ACK, FIN, ACK.

## DNS resolution order

1. Browser cache
2. OS cache
3. Configured resolver
4. Root -> TLD -> authoritative

## Commands

```bash
ss -tulpn
dig +short example.com
```
