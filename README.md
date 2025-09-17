# Advanced HomeLab Services & Security

*by [szy-cmd](https://github.com/szy-cmd)*

An evolving personal homelab combining media automation, virtualization, and security.

## Current Stack

### Media Infrastructure
- **[Jellyfin](https://github.com/jellyfin/jellyfin)** - Self-hosted media streaming server with transcoding support
- **[Shoko](https://github.com/shokoanime)** - Anime metadata management with AniDB integration
- **[Sonarr](https://github.com/Sonarr/Sonarr)** - Automated TV show downloading and organization
- **[Radarr](https://github.com/Radarr/Radarr)** - Automated movie downloading and library management
- **[Prowlarr](https://github.com/Prowlarr/Prowlarr)** - Indexer manager for torrent and usenet sources

*Media automation pipeline is fully operational with end-to-end content acquisition and library integration.*

## Roadmap

### Phase 1: Network Security & Remote Access
- **VPN and secure remote access** - WireGuard/OpenVPN setup for secure external connectivity
- **Reverse proxy** - NGINX/Traefik configuration for secure service exposure
- **Firewall hardening + VLAN isolation** - Network segmentation and traffic filtering

### Phase 2: Monitoring & Security Tools
- **Grafana + Prometheus dashboards** - Comprehensive system and service monitoring
- **IDS/IPS tools** - Wazuh, Suricata, and Fail2Ban for intrusion detection and prevention

### Phase 3: Virtualization & Development
- **VM environments** - Isolated test environments using Proxmox/ESXi
- **F1 Strategy AI project** - Hosting custom AI application in secure VM with web access

## Changelog

- **v0.1** - Initial Setup (Jellyfin + Shoko configuration)
- **v0.2** - Media Automation (Sonarr, Radarr, Prowlarr integration)
- **v0.3** - Documentation (Repository structure and README)
- **v0.4** - VPN and remote access implementation
- **v0.5** - Reverse proxy and SSL configuration
- **v0.6** - Network security and monitoring setup
- **v0.7** - Virtualization and AI project hosting

## Highlights

*Jellyfin episode metadata display with detailed information and artwork*
![Jellyfin Episode Metadata](./assets/screenshots/jellyfin/jellyfin-ep-metadata.jpg)

*Jellyfin playback interface showing media preview and controls*
![Jellyfin Playback Preview](./assets/screenshots/jellyfin/jellyfin-playback-preview.jpg)

*Sonarr automation dashboard showing active series monitoring and download queue*
![Sonarr Main Dashboard](./assets/screenshots/sonarr/sonarr-main.jpg)

*Shoko server interface showing AniDB metadata integration and anime organization*
![Shoko Main Dashboard](./assets/screenshots/shoko/shoko-main.jpg)

## Documentation

- [Roadmap](./docs/roadmap.md) - Detailed development phases and milestones
- [Changelog](./docs/changelog.md) - Complete version history and updates
- [Integration Guide](./docs/integration-guide.md) - Technical setup and configuration details
- [Screenshots](./docs/screenshots.md) - Visual documentation of the homelab setup

## Repository Structure

```
adv-homelab-sec/
├── docs/                    # Documentation and guides
├── assets/screenshots/      # Visual documentation
├── notes/                   # Development notes and research
├── configs/                 # Configuration files and templates
└── README.md               # Project overview
```

## Project Status

This project is actively maintained and regularly updated. The homelab continues to evolve with new services, security enhancements, and automation improvements. Check the [changelog](./docs/changelog.md) for recent updates and the [roadmap](./docs/roadmap.md) for upcoming features.

---

*Last updated: 2024-12-19*