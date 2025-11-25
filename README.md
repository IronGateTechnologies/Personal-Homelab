Welcome to my homelab documentation repo.
This repository is a living record of my homelab journey — from hardware builds and upgrades to networking diagrams, service deployments, and personal notes.

The homelab serves both as a sandbox for learning cybersecurity and networking and a playground for tinkering with hardware, virtualization, and storage.


---

Goals of This Repo

Document each node in the homelab with hardware specs, photos, and configurations

Keep history logs of upgrades, swaps, and experiments

Share wins, failures, and lessons learned (update journal)

Provide reproducible setups for anyone following along

Track the growth of the lab over months and years

Current Nodes

Alpha – Ryzen 9 powerhouse for testing; dual-boots Linux Mint and a Talon-Debloated Windows 11
Bravo – Renewed HP Envy business-class laptop running Linux Mint
Charlie – Dedicated storage and backup server
Delta – High-performance Proxmox server
Echo – Home Theater PC / Gaming Center running Bazzite Linux
Golf – ThinkPad T440 with Linux Mint (field laptop for off-site work)
Hotel – HP Printer/Scanner for document backups and digitization
India – Dell PowerEdge R710 running Proxmox, ensuring no enterprise-grade resources go underutilized

Upcoming/Planned Adds:

2× Dell Wyse 5070 SFF units

One will serve as a router using a USB 3.0 → Ethernet adapter

The other will be implemented in a LAN security / monitoring capacity

3× Budget Gaming PCs

Built for resale; if not sold, will be added as low-power homelab nodes with efficiency-tuned BIOS profiles

Each node has its own folder with detailed specs, history logs, and photos.

Journals

The journals/ directory contains dated entries documenting:

hardware changes

upgrades & repairs

experiments

service deployments

architectural changes

This acts as a living lab notebook chronicling the evolution of the entire setup.

Technologies in Use

Virtualization: Proxmox, VirtualBox
Storage: SMB/NFS shares, RAID configurations, backup workflows
Networking: VLANs, firewall rules, switch configuration, topology diagrams
Operating Systems: Bazzite Linux, Windows 11, Linux Mint, TrueNAS Scale
