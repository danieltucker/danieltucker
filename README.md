<!--
  GitHub Profile README
  Replace danieltucker with your GitHub handle everywhere it appears.
  Swap socials, badge colors, and links to taste.
-->

<div align="center">

# Hi, I'm Daniel

### Senior Solutions Architect · Builder of Self-Hosted Things · Homelab Enthusiast

I design and ship production systems for enterprise clients by day, and run a small fleet of self-hosted tools, side projects, and a local hosting business by night. I like infrastructure I can reason about end to end, and software that earns its keep.

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/danieltucker)
[![Website](https://img.shields.io/badge/Bellingham_Hosting-1A1A1A?style=for-the-badge&logo=cloudflare&logoColor=white)](https://your-site.com)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:you@example.com)

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

> A "Watch" family of self-hosted apps plus a couple of standalone products. Naming convention is half the fun.

### 🔭 Seer — Self-Hosted LLM Gateway
A routing layer that sits above my app stack and dispatches LLM requests from each service to the right Ollama instance. Centralizes model access, keeps inference on my own hardware, and gives every downstream app a single, consistent entry point.
`Node.js` · `Ollama` · `self-hosted`

### 📊 NetWatch — Uptime Monitoring
Service uptime and health monitoring with its own static marketing site. Deployed and running in production on my homelab.
`Node.js` · `Docker` · `monitoring`

### ⏱️ Quarters & Credits — Focus Timer (shipped to the App Store)
A cross-platform focus timer with a points-and-rewards economy spanning iOS, macOS, and web. Live on the App Store.
`Swift` · `SwiftUI` · `cross-platform`

### 🔁 Syncbase — Schema-Agnostic Sync Backend
A reusable sync engine designed to back Quarters & Credits and future projects, so new apps get offline-friendly data sync without reinventing it each time.
`backend` · `sync` · `architecture`

### 🔥 CronFire — Cron as a Service
A scheduling service that turns cron jobs into a managed, observable resource.
`Node.js` · `scheduling`

### ✉️ PenPaLLM — Email-to-LLM Bridge
Routes inbound email into an LLM and replies back out, built on Cloudflare Email Routing and Resend.
`Cloudflare` · `Resend` · `LLM`

---

## 🏗️ Homelab & Infrastructure

The lab where most of the above actually runs:

| Layer | Stack |
|---|---|
| **Virtualization** | Proxmox (3-node cluster) |
| **Orchestration** | k3s |
| **Storage** | TrueNAS — EPYC 7402, 128GB RAM, RTX 3090 |
| **Networking** | UniFi |
| **Media / AI** | Plex (NVENC), Ollama, Homebridge / HomeKit |

I run real workloads on this, which means I've debugged the unglamorous parts too: backplane faults, resilver events, GPU swaps breaking the apps service, IPMI fan control on Supermicro boards. The kind of problem-solving that doesn't show up in a tutorial.

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