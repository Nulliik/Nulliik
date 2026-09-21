# Hi there, I'm Null (@Nulliik) 👋

[![GitHub Followers](https://img.shields.io/github/followers/Nulliik?label=Followers&style=flat-square&color=blue)](https://github.com/Nulliik)
[![GitHub Stars](https://img.shields.io/github/stars/Nulliik?label=Total%20Stars&style=flat-square&color=gold)](https://github.com/Nulliik)
[![Public Repos](https://img.shields.io/badge/Repos-Public-informational?style=flat-square&color=blueviolet)](https://github.com/Nulliik?tab=repositories)

Software engineer and systems developer focused on **decentralized peer-to-peer networking**, **cross-platform applications**, **embedded firmware**, and **local AI/LLM inference optimization**.

---

## 🚀 Featured Open Source Projects

Here are the key open source projects I maintain and contribute to:

### 💬 [2pchat](https://github.com/Nulliik/2pchat) — Decentralized Peer-to-Peer Messenger
[![Language: Kotlin & Go](https://img.shields.io/badge/Languages-Kotlin%20%7C%20Go%20%7C%20Python-blue?style=flat-square)](https://github.com/Nulliik/2pchat)
[![Platform: Android & Desktop](https://img.shields.io/badge/Platform-Android%20%7C%20Linux%20%7C%20Windows-green?style=flat-square)](https://github.com/Nulliik/2pchat)
[![Security: End-to-End Encrypted](https://img.shields.io/badge/Security-Authenticated%20E2EE-red?style=flat-square)](https://github.com/Nulliik/2pchat)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](https://github.com/Nulliik/2pchat/blob/main/LICENSE.txt)

**[2pchat](https://github.com/Nulliik/2pchat)** is an autonomous, serverless **P2P messenger** designed for secure, censorship-resistant private communication without central servers or phone-number bindings.

- **Native Android Client**: Modern Android app built with **Kotlin** and **Jetpack Compose**, powered by a high-throughput, low-latency **Go network core** (`2pchatGO/android/core-go`).
- **Desktop Client**: Cross-platform Python client featuring a CLI chat, **Kivy GUI**, and a **FastAPI backend** for integration.
- **Cryptographic Protocols**: Messages are exchanged through mutually authenticated, end-to-end encrypted sessions with custom **Pairwise** and **Group Chat protocols**.
- **Resilient Peer Discovery**: Flexible routing and NAT traversal adapted to dynamic network conditions and decentralized topologies.

🔗 **Quick Links**:
- 📦 **Source Code**: [github.com/Nulliik/2pchat](https://github.com/Nulliik/2pchat)
- 📐 **Architecture & Tech Spec**: [2PCHAT_TECHNICAL_SPECIFICATION.md](https://github.com/Nulliik/2pchat/blob/main/2PCHAT_TECHNICAL_SPECIFICATION.md)
- 📜 **Pairwise Protocol**: [docs/PROTOCOL.md](https://github.com/Nulliik/2pchat/blob/main/docs/PROTOCOL.md)
- 👥 **Group Chat Protocol**: [docs/GROUP_CHAT_PROTOCOL.md](https://github.com/Nulliik/2pchat/blob/main/docs/GROUP_CHAT_PROTOCOL.md)

---

### 🎴 [STCardsBrowser](https://github.com/Nulliik/STCardsBrowser) — Full-Screen SillyTavern Character & Lorebook Extension
[![Extension: SillyTavern](https://img.shields.io/badge/Extension-SillyTavern-8A2BE2?style=flat-square)](https://github.com/Nulliik/STCardsBrowser)
[![Frontend: JavaScript](https://img.shields.io/badge/Stack-JavaScript%20%7C%20CSS3%20%7C%20HTML5-orange?style=flat-square)](https://github.com/Nulliik/STCardsBrowser)
[![Features: Anti-Slop Heuristics](https://img.shields.io/badge/Feature-Anti--Slop%20Heuristics-brightgreen?style=flat-square)](https://github.com/Nulliik/STCardsBrowser)
[![License: WTFPL+](https://img.shields.io/badge/License-WTFPL%2B-lightgrey?style=flat-square)](https://github.com/Nulliik/STCardsBrowser/blob/main/LICENSE)

**[STCardsBrowser](https://github.com/Nulliik/STCardsBrowser)** is a full-featured, full-screen extension for [SillyTavern](https://github.com/SillyTavern/SillyTavern) to explore, search, filter, and manage AI character cards, lorebooks, and local libraries.

- **Unified Multi-Source Discovery**: Search and browse across major repositories including *Chub, JannyAI, Character Tavern, Sakura.fm, Wyvern, CharaVault, Harpy.chat, RisuRealm, Backyard.ai, CrushOn.AI, Botify.ai, Joyland.ai, SpicyChat, Talkie AI, Pygmalion*, and trending feeds.
- **Local Character & World Info Manager**: Built-in editors for SillyTavern World Info files and character cards, with instant chat launching and one-click import/update.
- **Anti-Slop Heuristic Quality Scoring**: An explainable heuristic engine evaluating definition depth, greetings, dialogue examples, and metadata signals to flag low-effort cards and highlight high-quality community creations.
- **Search & Safety Controls**: Global tag querying (`+tag` / `-tag`), source-specific filters, NSFW blur/hide options, and favorite creator aggregation.

🔗 **Quick Links**:
- 📦 **Source Code**: [github.com/Nulliik/STCardsBrowser](https://github.com/Nulliik/STCardsBrowser)
- ⚡ **Installation Guide**: [How to install in SillyTavern](https://github.com/Nulliik/STCardsBrowser#install)
- 🗺️ **Codebase Structure**: [PROJECT_STRUCTURE.md](https://github.com/Nulliik/STCardsBrowser/blob/main/PROJECT_STRUCTURE.md)

---

### 📟 [SSD1306_library](https://github.com/MaxFlatline/SSD1306_library) — Embedded OLED Display Library for STM32
[![Hardware: STM32](https://img.shields.io/badge/Hardware-STM32L0%20%7C%20STM32F0-002B49?style=flat-square)](https://github.com/MaxFlatline/SSD1306_library)
[![Language: Embedded C](https://img.shields.io/badge/Language-Embedded%20C-00599C?style=flat-square)](https://github.com/MaxFlatline/SSD1306_library)
[![Interface: I2C / SPI](https://img.shields.io/badge/Interface-I2C%20%7C%20SPI-blueviolet?style=flat-square)](https://github.com/MaxFlatline/SSD1306_library)

The **[SSD1306_library](https://github.com/MaxFlatline/SSD1306_library)** is an efficient, lightweight embedded C driver for 0.96" and 1.3" SSD1306 OLED display modules on ARM Cortex-M microcontrollers (specifically STM32L0 and STM32F0 series).

- **Frame-based Refresh**: High-efficiency full-buffer graphics and text rendering pipeline.
- **Hardware Agnostic Transport**: Flexible hardware abstraction layer — easily portable to any MCU by implementing the single `OLED_SendData` wrapper in `oled_0_96.c`.
- **Low Memory Footprint**: Tailored for resource-constrained microcontrollers with minimal RAM overhead.

🔗 **Quick Links**:
- 📦 **Source Code**: [github.com/MaxFlatline/SSD1306_library](https://github.com/MaxFlatline/SSD1306_library)

---

## 🛠️ Technical Stack & Skills

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages** | Go, Kotlin, Python, Embedded C/C++, TypeScript, JavaScript |
| **Mobile & Desktop** | Android SDK, Jetpack Compose, Kivy, FastAPI, WebUI |
| **Networking & Security** | P2P Protocols, E2EE Cryptography, NAT Traversal, Socket & RPC |
| **Embedded Systems** | STM32 (L0/F0), ARM Cortex-M, Keil MDK, FreeRTOS, I2C/SPI Drivers |
| **AI / LLM Infrastructure** | Intel Arc Battlemage (Dual B60 48GB), llama.cpp, Vulkan, SYCL, vLLM, OpenVINO, GGUF/AWQ Quantization |

---

## 📈 Activity & Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Nulliik&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Nulliik GitHub stats" width="48%">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nulliik&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%">
</p>

---

<details>
<summary>🔍 <b>Topics & Keywords for Crawlers / Search Engines</b></summary>

- **2pchat**: P2P messenger, peer-to-peer messenger, decentralized chat, serverless messaging, encrypted messaging, Android Kotlin Compose, Go network core, Python desktop messenger, end-to-end encryption.
- **STCardsBrowser**: SillyTavern extension, SillyTavern card browser, character card finder, lorebooks editor, Chub browser, JannyAI cards, Anti-Slop filter, AI roleplay assistant extension.
- **SSD1306_library**: STM32 SSD1306 OLED driver, embedded C OLED display library, STM32L0, STM32F0, I2C OLED display, frame buffer refresh.
</details>
