# Awesome-Virtual-Desktop-Infrastructure-Vdi-DaaS

## Top Virtual Desktop Infrastructure (VDI / DaaS) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Remote Desktops, Application Streaming & Self-Hosted VDI Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial VDI/DaaS platforms** and **open-source projects** that deliver virtual desktops and applications to any device. These tools enable remote work, BYOD, and secure access to corporate resources without managing physical endpoints.



**Examples** include Amazon WorkSpaces, Microsoft Azure Virtual Desktop, Windows 365 Cloud PC, Citrix DaaS, VMware Horizon Cloud, Workspot, Parallels RAS, Nutanix Frame, Kasm Workspaces, and Apporto (the category leaders).



**Open-source emphasis**: VDI is a strong open-source domain. **Kasm Workspaces** leads as the most complete open-source containerized VDI platform with 10,000+ GitHub stars . **Apache Guacamole** provides clientless remote desktop gateway, while **Wolf** and **Sunshine**/ **Moonlight** deliver game/desktop streaming. **openvdi** brings a modern TypeScript-based VDI platform, and **Proxmox VE** provides the virtualization foundation. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon WorkSpaces](https://aws.amazon.com/workspaces/)**  

  AWS's managed desktop virtualization — Windows and Linux desktops in the cloud. **Best for AWS-centric organizations** wanting managed VDI.



- **[Microsoft Azure Virtual Desktop](https://azure.microsoft.com/en-us/products/virtual-desktop/)**  

  **Microsoft's comprehensive VDI platform** — multi-session Windows 10/11, RemoteApp, and FSLogix profile management. **The best for Windows-centric organizations** .



- **[Windows 365 Cloud PC](https://www.microsoft.com/windows-365)**  

  **Microsoft's cloud PC offering** — personalized Windows desktop streamed to any device. **The simplest Microsoft VDI** — per-user monthly pricing.



- **[Citrix DaaS](https://www.citrix.com/)**  

  **The enterprise VDI standard** — desktop and app virtualization with HDX protocol. **The reference for enterprise VDI** .



- **[VMware Horizon Cloud](https://www.vmware.com/products/horizon.html)**  

  VMware's VDI platform (now Omnissa) — virtual desktops and apps with Blast protocol.



- **[Workspot](https://www.workspot.com/)**  

  **Cloud-native VDI** — simple deployment on Azure, AWS, and GCP. **Best for cloud-first VDI** .



- **[Parallels RAS](https://www.parallels.com/products/ras/)**  

  **Application and desktop virtualization** — cost-effective Citrix alternative. **Best for SMBs wanting VDI** .



- **[Nutanix Frame](https://www.nutanix.com/products/frame)**  

  **Cloud-native DaaS** — desktop and app streaming from any cloud. **Best for Nutanix ecosystem users** .



- **[Kasm Workspaces](https://kasmweb.com/)**  

  **The leading commercial containerized VDI** — see Open-Source section below for the community edition.



- **[Apporto](https://www.apporto.com/)**  

  **Cloud desktop for education** — virtual computer labs and app streaming for universities. **Best for educational institutions** .



## Open-Source GitHub Projects



- **[Kasm Workspaces (Community Edition)](https://github.com/kasmtech/workspaces-core-images)**  

  **The leading open-source containerized VDI platform**, Apache-2.0 licensed with **10,000+ GitHub stars** (main repo) . **Streams containerized desktops and applications to browsers** — no client software required . **Supports Linux desktops (Ubuntu, Debian, Alpine, Fedora), Windows apps via Wine, and browser-based tools** . **The de facto open-source VDI alternative** — used by enterprises, government, and defense . **Community Edition free**; Enterprise/Pro for advanced features . **Best for browser-based VDI with container isolation** .



- **[Apache Guacamole](https://github.com/apache/guacamole-server)**  

  **Clientless remote desktop gateway**, Apache-2.0 licensed with **3,000+ GitHub stars** . **Access desktops via HTML5 browser** — no plugins or client software . **Supports VNC, RDP, and SSH protocols** . **The most widely deployed open-source remote desktop gateway** . **Best for simple browser-based remote access** .



- **[Wolf](https://github.com/games-on-whales/wolf)**  

  **Streaming server for Moonlight clients**, MIT licensed with **2,000+ GitHub stars** . **Runs Windows games and applications in containers on Linux** . **The easiest way to stream Windows apps from Linux** . **Best for game and app streaming** .



- **[Sunshine](https://github.com/LizardByte/Sunshine)**  

  **Open-source game streaming host**, GPL-3.0 licensed with **15,000+ GitHub stars** . **Self-hosted alternative to NVIDIA GameStream** . **The leading open-source streaming host** . **Best paired with Moonlight for desktop streaming** .



- **[Moonlight](https://github.com/moonlight-stream/moonlight-qt)**  

  **Open-source game streaming client**, GPL-3.0 licensed with **10,000+ GitHub stars** . **Client for Sunshine and NVIDIA GameStream** . **The standard open-source streaming client** . **Best paired with Sunshine** .



- **[openvdi](https://github.com/openvdi/openvdi)**  

  **Open-source Virtual Desktop Infrastructure platform**, AGPL-3.0 licensed . **Modern TypeScript/Node.js architecture** . **Self-hosted VDI with web interface** . **Best for modern web-based VDI** .



- **[Proxmox VE](https://github.com/proxmox/pve-manager)**  

  **The leading open-source virtualization platform**, AGPL-3.0 licensed . **KVM and LXC with web management** — foundation for self-hosted VDI . **SPICE and noVNC console access** . **Best for self-hosted VDI infrastructure** .



- **[XCP-ng](https://github.com/xcp-ng/xcp)**  

  **Open-source Xen-based hypervisor**, GPL-2.0 licensed . **Enterprise virtualization with Xen Orchestra web interface** . **Best for Xen-based VDI** .



- **[oVirt](https://github.com/oVirt/ovirt-engine)**  

  **Open-source virtualization management**, Apache-2.0 licensed . **KVM-based with web management** . **Best for enterprise KVM VDI** .



- **[OpenStack** — Open-source cloud infrastructure with Nova compute for VDI workloads . **Best for large-scale private cloud VDI** .



- **[Apache CloudStack** — Open-source cloud platform with VDI capabilities . **Best for service provider VDI** .



- **[oVirt** — Already listed. **KVM-based virtualization management** .



### Application Streaming



- **[AppStream](https://github.com/AppStream/AppStream)** — Linux application streaming (not VDI but related) .



- **[Xpra](https://github.com/Xpra-org/xpra)**  

  **Screen-for-X with HTML5 client**, GPL-2.0 licensed . **Remote application access with browser client** . **Best for Linux application streaming** .



- **[x11vnc](https://github.com/LibVNC/x11vnc)**  

  **VNC server for real X displays**, GPL-2.0 licensed . **The standard for X11 remote access** . **Best for Linux remote desktop** .



- **[TigerVNC](https://github.com/TigerVNC/tigervnc)**  

  **High-performance VNC server and client**, GPL-2.0 licensed . **The most actively maintained VNC implementation** . **Best for cross-platform VNC** .



- **[noVNC](https://github.com/novnc/noVNC)**  

  **HTML5 VNC client**, MPL-2.0 licensed with **10,000+ GitHub stars** . **Browser-based VNC access** . **Best for web-based VNC** .



### Container-Based Desktops



- **[Kasm Workspaces](https://github.com/kasmtech/workspaces-core-images)** — Already listed. **The leading containerized VDI** .



- **[linuxserver/webtop](https://github.com/linuxserver/docker-webtop)**  

  **Containerized desktop environments with web access**, GPL-3.0 licensed . **XFCE, KDE, MATE, and i3 desktops in browser** . **The simplest containerized desktop** . **Best for quick browser-based Linux desktops** .



- **[Selkies](https://github.com/selkies-project/selkies-gstreamer)**  

  **Open-source GPU-accelerated remote desktop**, MPL-2.0 licensed . **WebRTC-based with GStreamer** . **The best open-source GPU-accelerated VDI** . **Best for GPU workloads and game streaming** .



- **[Selkies GPU Desktops](https://github.com/selkies-project/docker-nvidia-glx-desktop)**  

  **KDE Plasma desktop with GPU acceleration**, MPL-2.0 licensed . **NVIDIA GPU-accelerated container** . **Best for GPU-accelerated Linux desktops** .



- **[Neko](https://github.com/m1k1o/neko)**  

  **Virtual browser in Docker**, Apache-2.0 licensed . **Shared browser sessions** . **Best for collaborative browsing** .



### Additional Strong Open-Source Options



- **UDL (Universal Desktop Linux)** — Open-source remote desktop with browser client .

- **xrdp** — Open-source RDP server for Linux .

- **FreeRDP** — Open-source RDP client .

- **Remmina** — Open-source remote desktop client .

- **KRDC** — KDE remote desktop client .

- **Vinagre** — GNOME VNC client .

- **TightVNC** — Open-source VNC .

- **UltraVNC** — Open-source VNC with Windows support .

- **MeshCentral** — Web-based remote management with desktop access .

- **RustDesk** — Open-source remote desktop (TeamViewer alternative) .



**Frameworks for building custom VDI solutions**: Combine **Kasm Workspaces** for containerized browser-based VDI . Use **Apache Guacamole** for clientless remote desktop gateway . Deploy **Proxmox VE** or **XCP-ng** as the virtualization foundation . Choose **Selkies** for GPU-accelerated remote desktops . Use **Wolf** + **Moonlight** for Windows app streaming from Linux . Integrate **linuxserver/webtop** for quick containerized Linux desktops . Note that true enterprise VDI with HDX/Blast protocols, profile management, and vendor-supported SLAs (Citrix, VMware Horizon, Azure Virtual Desktop) remains primarily commercial territory; open-source stacks provide strong containerized desktops, remote access, and virtualization foundations that require integration for complete enterprise VDI.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- VDI platforms provide access to sensitive corporate desktops and data. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **GPU acceleration adds complexity** — Selkies and Wolf require GPU passthrough and driver configuration . Evaluate GPU requirements before deployment.

- **Containerized VDI (Kasm, linuxserver/webtop) is not a full VDI replacement** — it excels at browser-accessible Linux desktops and app streaming but lacks the profile management, session brokering, and enterprise policy controls of Citrix or VMware Horizon .

- **Remote access protocols have trade-offs** — RDP for Windows, VNC for Linux, SPICE for Proxmox, and WebRTC for browser-based streaming. Choose based on your workload and client requirements.

- The open-source ecosystem provides strong containerized desktops, remote access, and virtualization foundations, but **HDX/Blast protocols, profile management, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for IT administrators, remote work teams, and organizations seeking VDI sovereignty.**  

Let's make virtual desktop infrastructure more open, transparent, and accessible.
