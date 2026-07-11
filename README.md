<div align="center">

<img src="assets/banner.svg" alt="VANAKKA — SYS_STATUS: NOMINAL · homelabs, ML agents, game mods" width="100%" />

<br/>

[<img src="https://img.shields.io/badge/vanakka.com-visit_the_site-3344DD?style=for-the-badge&logo=astro&logoColor=white" alt="vanakka.com" />](https://vanakka.com)
[<img src="https://img.shields.io/badge/X-@Vanakka-1DA1F2?style=for-the-badge&logo=x&logoColor=white" alt="X" />](https://x.com/Vanakka)
[<img src="https://img.shields.io/badge/Email-Dev@Vanakka.com-E8272C?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />](mailto:Dev@Vanakka.com)
[<img src="https://img.shields.io/badge/Discord-ask_me-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />](https://discord.com)

</div>

<div align="center">

<img src="https://raw.githubusercontent.com/Vanakka/Vanakka/output/lorekeeper.svg" alt="The Lorekeeper's thought for the day — rotates daily" />

</div>

## 🚀 // projekts.db · indexed

|     | project | status | what it is |
| :-: | :------ | :----: | :--------- |
| 🔴 | **proxmox homelab** | `always on` | Custom Proxmox server on ZFS — Debian containers, AMP game servers, media stack, Cloudflare Zero Trust tunnels |
| 🟠 | **anime/manga tracker** | `active dev` | Local-first Electron library + Chrome extension progress sync · SQLite · AniList/Jikan/MangaUpdates enrichment · 209 tests |
| 🟢 | **game modding tools** | `shipped` | Creation tooling for HOI4, Stellaris & Software Inc — batch generators for grand-strategy modding |
| 🟣 | **budget secure** | `active dev` | Offline Flutter finance app (Windows + Android) · SQLCipher + biometric unlock · zero cloud, zero analytics |
| 🔵 | **lorekeeper 40k** | `shipped` | Gemma 4 E4B fine-tune that narrates as a weary 40K witness — QLoRA, 500 hand-written examples, TTS-clean GGUF builds |
| ⭐ | **starmap foundry** | `ongoing` | Local 3D galaxy editor — Tauri 2 + Babylon.js 9 + Rust Keplerian math, binary/trinary systems, Holman-Wiegert stability |

> 🖥️ All of it lives at **[vanakka.com](https://vanakka.com)** — diagonal tabs, a live packet mesh, and a terminal that occasionally crashes the whole site on purpose. Try `vanakka.com/#crash`.

## 📊 // telemetry

<div align="center">

<a href="https://vanakka.com"><img src="https://img.shields.io/website?url=https%3A%2F%2Fvanakka.com&style=for-the-badge&label=vanakka.com&up_message=NOMINAL&up_color=76C41C&down_message=OFFLINE&down_color=E8272C" alt="vanakka.com status" /></a>
<a href="https://toc.vanakka.com"><img src="https://img.shields.io/website?url=https%3A%2F%2Ftoc.vanakka.com&style=for-the-badge&label=toc.vanakka.com&up_message=NOMINAL&up_color=76C41C&down_message=OFFLINE&down_color=E8272C" alt="toc.vanakka.com status" /></a>
<img src="https://komarev.com/ghpvc/?username=Vanakka&style=for-the-badge&color=8B5CF6&label=PROFILE+SCANS" alt="profile views" />

</div>

```console
root@vanakka:~$ lab-monitor --status
● zpool nvme            ONLINE · scrub repaired 0B · 0 errors
● services              47/47 running
● cloudflare tunnels    2 active · 0 open ports
● projekts indexed      6 (2 shipped · 3 active dev · 1 ongoing)
● test suites           209 passing (tracker) · rust + playwright (starmap)
● local ml              gemma-4-e4b fine-tune · q8_0 + q4_k_m gguf
● cloud dependencies    0
root@vanakka:~$ _
```

<div align="center">

<img src="https://raw.githubusercontent.com/Vanakka/Vanakka/output/github-contribution-grid-snake-dark.svg?v=2" alt="Contribution snake" />

</div>

## 💻 // stack.manifest

<div align="center">

<img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white" alt="Proxmox" />
<img src="https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white" alt="Debian" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" />
<img src="https://img.shields.io/badge/ZFS-2CA5E0?style=for-the-badge&logo=openzfs&logoColor=white" alt="ZFS" />
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust (curious)" />
<img src="https://img.shields.io/badge/GDScript-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" alt="Godot / GDScript" />
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
<br/>
<img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron" />
<img src="https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" />
<img src="https://img.shields.io/badge/Tauri-24C8D8?style=for-the-badge&logo=tauri&logoColor=white" alt="Tauri" />
<img src="https://img.shields.io/badge/llama.cpp-local_ML-76C41C?style=for-the-badge&logo=ollama&logoColor=white" alt="llama.cpp" />
<img src="https://img.shields.io/badge/Unsloth-QLoRA-8B5CF6?style=for-the-badge" alt="Unsloth QLoRA" />

</div>

## 🏠 // homelab.rack

| node | runs | why |
| :--- | :--- | :--- |
| **Proxmox VE** | the whole show | hypervisor + ZFS pool, scrub-clean |
| **Debian CTs** | game servers · media · bots | AMP-managed dedicated servers, self-hosted media stack |
| **Cloudflare Tunnels** | secure ingress | zero open ports, Zero Trust access |
| **Local ML box** | llama.cpp · fine-tunes | GGUF quants, agent pipelines, no cloud inference |

---

<div align="center">

```text
> Awaiting tab selection_
```

<sub>profile auto-generated? no. hand-tuned like everything else here. · last human update: 2026-07</sub>

</div>
