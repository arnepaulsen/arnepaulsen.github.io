---
layout: post
title: Bauer Home Topology
date: 2023-04-04 10:00:00 -700
categories: topology, streaming
tags: hardware, software, networking
---

Documentation of the Bauer home hardware, software and networking topologies.


# Physical Systems

* [Windows 11]({% post_url 2023-04-02-Windows11 %})
* [Fedora  37]({% post_url 2023-04-02-Fedora-Desktop %})
* Red Hat 8.7 
* Dell PowerEdge - VMWare
* HP Proliant - Proxmox
* Intel Z170 Wifi - TrueNas
* Ubuntu Desktop Survellance
* Ubuntu Desktop Test Frame


# Hypervisors
* VmWare
* Proxmox

# Networking

* Procectli 4-Port
* Engenius WiFi Garage
* Engenius WiFi Family Room
* Engenius WiFi Bedrooms
* Netgear 16-Port Switch LAN
* Netgear 8-Port Wireless
* Netgear 8-Port Secure


# Web Hosts

* Linode Docker/Apache2
* Fedora Podman/Apache2
* Red Hat Podman/Apache2
* GitHub Pages

# Web Sites

* Arne Paulsen Jr
* Paulsen Networks
* Paulsen IT Solutions
* Jekyll Static Site Generator
* Portainer
* MyPHP Admin for SQL

# SmartHome

* Home Assistant
* SmartThings
* Philips Hue
* Google Home

# How to Publish

* 1. export gitmsg="some message"
* 2. then do:

```bash

cd ~/Projects/arnepaulsen.github.io 
git status
git add .
git status
git commit -m "feat(post): $gitmsg"
git push
```