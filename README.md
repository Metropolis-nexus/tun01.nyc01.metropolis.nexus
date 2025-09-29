# tun01.nyc01.metropolis.nexus

- `rpm-ostree install firewalld`
- `rpm-ostree kargs --editor` -> Remove `console=tty0, console=ttyS0,115200`
- Setup NGINX as per [NGINX-Setup](https://github.com/Metropolis-nexus/NGINX-Setup)
