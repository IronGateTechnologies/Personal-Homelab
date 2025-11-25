Welcome to my homelab documentation repo.

This repository is a living record of my homelab journey — from hardware builds and upgrades to networking diagrams, service deployments, and personal notes.

The homelab serves both as a sandbox for learning cybersecurity and networking, and a playground for tinkering with hardware, virtualization, and storage.

Goals of This Repo

Document each node in the homelab with hardware specs, photos, and configurations

Keep history logs of upgrades, swaps, and experiments

Share wins, failures, and lessons learned (update journal)

Provide reproducible setups for anyone following along

Track the growth of the lab over months and years

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________


Current Nodes


Alpha – Ryzen 9 powerhouse for testing; dual-boot Linux Mint and a debloated version of Windows 11 (courtesy of the Talon Debloat Script)


Bravo – Renewed business-class HP Envy laptop running Linux Mint


Charlie – Storage and backup server


Delta – High-performance Proxmox server


Echo – Home Theater PC / Gaming Center running Bazzite Linux


Golf – ThinkPad T440 with Linux Mint (field laptop for out-of-office work)


Hotel – HP printer/scanner for document backup and digitizing


India – Dell PowerEdge R710 utilizing Proxmox so no resources are left underutilized


(I recently picked up two Dell Wyse 5070 SFF nodes — one will become my router with the addition of an Ethernet-to-USB 3.0 Male to RJ-45 Female adapter. The other will likely be implemented for LAN security purposes.)


(There are also three gaming PCs I put together on a budget in the hopes of selling them. In the event they are not sold, they will be utilized as additional nodes in the lab, running with power-efficient settings enabled at the BIOS level.)


Each node has its own folder with detailed specs, history, and photos.

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Journals

The journals directory contains dated records of hardware changes, upgrades, and experiments.
This serves as a lab notebook documenting the evolution of the setup.

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________


Technologies in Use

Virtualization: Proxmox, VirtualBox
Storage: SMB/NFS shares, RAID configurations
Networking: VLANs, firewall rules, switch configs
Operating Systems: Bazzite, Windows, Linux Mint, TrueNAS Scale
