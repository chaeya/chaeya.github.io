# nGuardian 

Secure WORM Storage OS

- Linux kernel 5.18.3
- GNU C Library 2.35
- Busybox 1.34.1


## Build

```
# Update all repositories and upgrade all packages
sudo apt update
sudo apt upgrade -y

# Resolve build dependencies
sudo apt install -y wget make gawk gcc bc bison flex xorriso libelf-dev libssl-dev

# Build ISO image
sudo ./build.sh
```
