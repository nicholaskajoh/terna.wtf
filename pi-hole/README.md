# Pi-hole
DNS and ad/tracking blocker.

URL: http://pi-hole.hl.terna.wtf

## Setup
- Configure Ubuntu for Pi-hole (netplan): https://github.com/pi-hole/docker-pi-hole#installing-on-ubuntu-or-fedora

- Run Pi-hole using Docker:
    ```sh
    export PIHOLE_WEBPASSWORD=xxxxx && docker compose up -d
    ```

- Configure recursive DNS resolver (unbound): https://docs.pi-hole.net/guides/dns/unbound/

- Configure the Pi-hole box as [a subnet router](https://tailscale.com/kb/1019/subnets/) for local home lab network:
    ```sh
    sudo tailscale up --accept-dns=false --advertise-routes=10.0.0.0/24
    ```

- Add block lists: https://firebog.net/
