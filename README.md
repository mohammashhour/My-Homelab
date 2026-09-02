# My-Homelab 💻👨‍💻

## Overview

This repository documents my personal homelab, which I use to learn and experiment with Linux, virtualization, networking, Docker, AI, and self-hosted services.
| Component | Technology |
| --- | ----------- |
| Hypervisor | Proxmox VE |
| Server | Dell PowerEdge R620 |
| CPU | 2× Intel Xeon E5-2630 v2 |
| RAM | 128 GB |
| GPU | NVIDIA Tesla P4 |
| OS | Debian / Ubuntu |
| SBC | Raspberry pi 4 B |
| Remote Access | Tailscale |

## Services & Purpose 

| Service | Purpose | Platform |
| --- | ----------- | -------- |
| Pi-hole | Blocks DNS queries to known ad/tracking domains | Raspberry pi |
| Tailscale | Allows me to access any of my services remotely when outside the network | Raspberry pi |
| Uptime Kuma | Allows me to monitor the status of services to see if they are up or down | Raspberry pi |
| Proxmox | Virtualization | Dell poweredge R620 |
| Open WebUI | Running my local hosted LLM by ollama  | Dell poweredge R620 |
| Crafty controller | provides tunneling so the Minecraft server can be reachable without traditional port forwarding | Dell poweredge R620 |
| playit.gg | Allows my minecraft server to be available to the internet | Raspberry pi |

## Virtualization

- AI and Robotic:
  Directly connected to The GPU
  It is used for personal AI projects and Robotic project involving Gazebo
- Hosting:
  Used for hosting webservers,email servers, Minecraft server, and jellyfin server

## Architecture

