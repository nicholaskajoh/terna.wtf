# Update Proxmox node

## Check version
```sh
pveversion
```

## Update
```sh
apt update && apt dist-upgrade -y
```

## Check version again
```sh
pveversion
```

## Reboot node
```sh
reboot
```
