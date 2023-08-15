# terna.wtf
Configs and docs for my home lab.

## Hardware
- 2x Fujitsu Esprimo Q920 mini PC (Intel Core i5-4590T CPU @ 2.00 GHz, 8 GB DDR3 RAM, 240 GB SSD)
- 1x TP-Link TL-WR841N router (300 Mbps wireless speed, 100 Mbps wired speed)
- 1x TP-Link Archer C80 router (1300 Mbps/5 GHz & 600 Mbps/2.4 GHz wireless speed, 1 Gbps wired speed)

## Software & services
- Proxmox (PVE): Hypervisor, for running VMs.
- Ubuntu: OS of choice for VMs.
- Pi-hole: DNS + ad/tracking blocker.
- Home Assistant (HAOS): Home automation system.
- Ceph: software-defined distributed storage.
- Tailscale: VPN service.
- Prometheus, Loki & Grafana: Collection and visualization of metrics and logs for the software systems running in the lab.
- Kubernetes: Orchestrator for running custom and third-party apps.
- Portainer: UI for managing Docker and Kubernetes.
- Keepalived: Virtual IP for Kubernetes cluster.

## Projects
- Home lab home page (WIP): Overview of all the software running in the lab.
- Home lab observability: Single platform for monitoring the lab.
- Ad & tracking blocker: Block all those pesky ads and trackers on all my devices and from any location I'm at. Run my own DNS resolver instead of using Google or Cloudflare.
- Indoor temperature & humidity tracker: Tracking the temperature and humidity at home, especially in the colder months.

## Future projects
- Energy usage tracker (real-time tracking of my energy usage by polling my electricity meter)
- Data analysis pipeline
- Authoritative DNS
- Home security camera
