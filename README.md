# Patches

### buster-backports wireguard compilation patch (version 1.0.20200712)
```bash
patch -d "$(find /var/lib/dkms/wireguard -maxdepth 1 -type d | tail -n1)/source/compat" < wireguard.patch
```
