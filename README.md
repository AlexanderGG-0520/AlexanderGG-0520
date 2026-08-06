<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,45:7c3aed,100:06b6d4&height=220&section=header&text=AlexanderGG&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Linux-first%20developer%20building%20faster%20Minecraft%20systems&descAlignY=58&descSize=18" alt="AlexanderGG header" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=22D3EE&center=true&vCenter=true&width=850&lines=Minecraft+rendering+%26+performance;Kubernetes-first+game+server+infrastructure;Linux+compatibility+engineering;Build+it.+Measure+it.+Make+it+reliable." alt="Typing introduction" />

<br />

[![Profile views](https://komarev.com/ghpvc/?username=AlexanderGG-0520&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS)](https://github.com/AlexanderGG-0520)
[![GitHub followers](https://img.shields.io/github/followers/AlexanderGG-0520?style=for-the-badge&logo=github&color=06b6d4&labelColor=0f172a)](https://github.com/AlexanderGG-0520?tab=followers)

</div>

## `whoami`

```text
Student developer in Japan
Linux-first / performance-minded / infrastructure-oriented
Building software around Minecraft, rendering, containers, and compatibility
```

I enjoy working below the surface of an application: render pipelines, protocol gateways, process lifecycles, persistent storage safety, compatibility layers, and reproducible deployment.

My goal is not merely to make something run. I want to understand **why it works**, measure whether it is actually better, and make failure modes explicit.

> **Compatibility before novelty. Evidence before performance claims. Safety before automation.**

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [Threadium](https://github.com/AlexanderGG-0520/threadium)

Experimental Fabric client optimization mod that accelerates eligible Minecraft `ModelPart` entity rendering through cached meshes, per-instance pose data, and GPU instancing.

- Safe vanilla fallback for unsupported render paths
- Differential correctness coverage
- Designed to coexist with established optimization mods
- Measured scaling improvements in dense entity scenes

</td>
<td width="50%" valign="top">

### [Minecartainer](https://github.com/AlexanderGG-0520/minecartainer)

A predictable, fail-fast Minecraft Java server container image designed for Kubernetes, GitOps, persistent volumes, and S3-compatible asset delivery.

- Minecraft-aware graceful shutdown through RCON
- Conservative persistent-volume handling
- Multiple Java runtime targets
- Fabric, Paper, Purpur, Forge, NeoForge, Velocity, and more

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AviUtl2 Linux Patches](https://github.com/AlexanderGG-0520/aviutl2-linux-patches)

Compatibility patches, reproducible build scripts, diagnostics, and an interactive setup flow for running AviUtl2 on x86_64 Linux.

- Patched Wine DirectWrite and DXVK
- Fcitx5 / Mozc Japanese input
- AV1 and NVIDIA NVDEC validation
- Provenance-aware artifact verification

</td>
<td width="50%" valign="top">

### [mc-router](https://github.com/AlexanderGG-0520/mc-router)

A Go-based Minecraft Java Edition gateway that routes one public TCP entry point to multiple backend servers using the hostname from the Minecraft handshake.

- Static and Kubernetes-discovered routing
- Prometheus metrics and structured logging
- Graceful shutdown and fail-closed behavior
- Experimental transfer-aware voice chat routing

</td>
</tr>
</table>

## What I work with

<div align="center">

### Languages and runtime

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C Sharp](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

### Infrastructure and platform

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=111827)
![Arch Linux](https://img.shields.io/badge/Arch%20Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)

### Development focus

![Minecraft](https://img.shields.io/badge/Minecraft-Modding-62B47A?style=for-the-badge&logo=modrinth&logoColor=white)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=for-the-badge&logo=opengl&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)

</div>

## Engineering principles

```yaml
performance:
  - benchmark before claiming improvement
  - optimize real bottlenecks, not impressive-looking microcases

reliability:
  - fail fast when state is ambiguous
  - preserve user data and provide safe fallback paths

compatibility:
  - integrate with the existing ecosystem
  - keep unsupported behavior explicit and recoverable

workflow:
  - automate repeatable work
  - keep builds and diagnostics reproducible
```

## Current focus

- Expanding Threadium from dense-entity wins toward broader real-world Minecraft performance
- Hardening Minecraft server delivery and routing for Kubernetes environments
- Improving Windows creative software compatibility on Linux without hiding unverified assumptions
- Building development environments where Linux is treated as a first-class platform

## GitHub activity

<div align="center">

<img width="100%" src="./profile-summary-card-output/tokyonight/0-profile-details.svg" alt="GitHub profile summary" />

<img width="49%" src="./profile-summary-card-output/tokyonight/1-repos-per-language.svg" alt="Repositories per language" />
<img width="49%" src="./profile-summary-card-output/tokyonight/2-most-commit-language.svg" alt="Most used commit languages" />

<img width="49%" src="./profile-summary-card-output/tokyonight/3-stats.svg" alt="GitHub stats" />
<img width="49%" src="./profile-summary-card-output/tokyonight/4-productive-time.svg" alt="Productive time" />

</div>

---

<div align="center">

### Build systems that are fast, observable, and difficult to break.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,55:7c3aed,100:0f172a&height=120&section=footer" alt="Footer" />

</div>
