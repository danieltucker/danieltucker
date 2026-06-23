<div align="center">

# Hi, I'm Daniel

### Senior Solutions Architect · Builder of Self-Hosted Things · Homelab Enthusiast

I design and ship production systems for enterprise clients by day, and run a small fleet of self-hosted tools, side projects, and a local hosting business by night. I like infrastructure I can reason about end to end, and software that earns its keep.

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/danieltucker)
[![Website](https://img.shields.io/badge/Bellingham_Hosting-1A1A1A?style=for-the-badge&logo=cloudflare&logoColor=white)](https://bellinghamhosting.com)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daniel.tucker+linkedin@outlook.com)

</div>

---

## 🛠️ What I Work With

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0071E3?style=flat-square&logo=swift&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/k3s-FFC61C?style=flat-square&logo=k3s&logoColor=black)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

</div>

I'm comfortable owning a feature from infrastructure to UI: provisioning the cluster, wiring the services, building the API, and shipping the client. Lately a lot of my building has centered on self-hosted LLM tooling and a reusable sync backend that lets me stand up new apps quickly.

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

<img src="images/NetWatch%20Logo.png" height="44" alt="NetWatch"><br><br>

Self-hosted uptime monitoring for developers, homelabbers, and small teams. Makes real HTTP/S, TCP, and ICMP checks on configurable intervals and pushes every result to the browser instantly via Server-Sent Events — no polling, no page refreshes. Supports Telegram, email, and SMS alerts; scheduled status reports; SSL certificate expiry tracking; and per-monitor embed widgets.

<br>

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<br>

[![View on GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/danieltucker/NetWatch)

<br><br>

<img src="images/NetWatch.png" width="100%" alt="NetWatch dashboard">

</td>
<td width="50%" valign="top">

<img src="images/BayWatch%20Logo.png" height="44" alt="BayWatch"><br><br>

Self-hosted drive bay map for NAS boxes and servers. Builds a visual grid of every drive and slot with live SMART health scores, temperature tracking, ZFS pool integration, warranty alerts, and federation across multiple hosts. Works on TrueNAS Scale, Unraid, or any Linux Docker host.

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<br>

[![View on GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/danieltucker/BayWatch)

<br><br> 

<img src="images/BayWatch.png" width="100%" alt="BayWatch dashboard">

</td>
</tr>
</table>

---

## 🏗️ Homelab & Infrastructure

The lab where most of the above actually runs:

| Layer | Stack |
|---|---|
| **Virtualization** | Proxmox — 3-node cluster |
| **Orchestration** | k3s |
| **Storage** | TrueNAS Scale — ZFS on Supermicro (AMD EPYC 7402P · 128 GB ECC RAM) |
| **GPU** | NVIDIA RTX 3090 — shared between Plex NVENC transcoding and Ollama inference |
| **Networking** | UniFi |
| **Home Automation** | Homebridge / HomeKit |

I run real workloads on this, which means I've debugged the unglamorous parts too: backplane faults, resilver events, the RTX 3090 getting pulled for a GPU swap and taking down both the media stack and local LLM inference at once, IPMI fan control on Supermicro boards, and k3s nodes that decide 3 AM is a good time to lose quorum. The kind of problem-solving that doesn't show up in a tutorial.

---

## 💼 Professionally

I'm a **Senior Solutions Architect** working in professional services on conversational AI platforms, leading client engagements from design through delivery. Day to day that's translating business requirements into working systems, owning technical decisions, and being the person clients trust to make it work in production.

On the side I run **Bellingham Hosting**, serving small businesses around Whatcom County, WA — websites, hosting, and the occasional rebuild.

---

## 📈 GitHub Stats

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=danieltucker&show_icons=true&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=danieltucker&layout=compact&hide_border=true)

![Streak](https://github-readme-streak-stats.herokuapp.com/?user=danieltucker&hide_border=true)

</div>

---

<div align="center">

When I'm not building, I'm usually on a motorcycle, in the garden, or playing something retro on a handheld.

*Let's build something.*

</div>