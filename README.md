# ⚡ NEXUS X // TERMINAL VPN

![NEXUS X Status](https://img.shields.io/badge/Status-Active-50FA7B?style=for-the-badge)
![Python Version](https://img.shields.io/badge/Python-3.10%2B-00F0FF?style=for-the-badge)
[![Download Release](https://img.shields.io/badge/Download-Latest_Release-50FA7B?style=for-the-badge&logo=github)](https://github.com/wsq4ka/Nexus-VPN-client/releases/tag/releases)
![Platform](https://img.shields.io/badge/Platform-Windows_10%20%7C%2011-8BE9FD?style=for-the-badge)

**NEXUS X** is an ultra-modern, high-performance desktop VPN client built with Python and PyQt6. Powered by the robust **Xray-core**, it features a cyberpunk-inspired terminal UI, fluid 60 FPS animations, and a zero-configuration system proxy engine designed to bypass aggressive OS routing bugs (including Windows 11 24H2).

---
<img width="545" height="296" alt="Снимок экрана 2026-04-17 214733" src="https://github.com/user-attachments/assets/0016d2d8-5f75-402d-bb4b-2461a4a428e1" />


## 🚀 Key Features

### 🛡️ Unbreakable Core (Powered by Xray)
* **Multi-Protocol Support:** Seamlessly decodes and connects to **VLESS, VMess, Trojan, and Shadowsocks** subscription links.
* **Advanced Transport:** Full support for `WebSocket (ws)`, `gRPC`, and `REALITY` security protocols.
* **Smart Routing & FakeDNS:** Built-in ad/tracker blocking (Blackhole) and FakeDNS implementation to prevent WebRTC/IPv6 leaks and bypass secure DNS hijackings in modern browsers.
* **Insecure Certificate Bypass:** Automatically handles non-standard or self-signed certificates from free proxy nodes.

### 💻 Zero-Config System Integration
* **Auto System Proxy:** Automatically modifies Windows Registry to set up the system proxy upon connection and cleanly restores it upon disconnection.
* **Windows 11 24H2 Proof:** Specifically engineered to bypass the new strict routing bugs in the latest Windows 11 updates. 
* **Portable Ready:** Caches your nodes and settings locally in `nexus_settings.json`. No installation required—just unzip and run.

### 🎨 Ultimate Liquid UI
* **Cyber Radar Splash:** A highly optimized 60 FPS holographic loading screen.
* **Borderless Design:** Draggable window with absolute positioning and hardware-accelerated fade-in effects.
* **Custom Fonts & Emojis:** Native support for custom `.ttf`/`.otf` fonts with smart fallbacks for Apple and Windows emojis.
* **Live System Log:** A dedicated right-panel terminal displaying real-time Xray traffic and system events in a classic monospace hacker aesthetic.

---

## 🛠️ Installation & Usage

### Option 1: Portable Version (Recommended)
1. Go to the [Releases](../../releases) page and download the latest `NexusVPN.rar`.
2. Extract the folder to any location on your PC.
3. Run `NexusVPN.exe` as **Administrator** (Required for System Proxy configuration).
4. Paste your subscription URL, hit **SYNC**, select a node, and click **INITIATE CONNECTION**.

### Option 2: Run from Source
1. Clone this repository:
   ```bash
   git clone [https://github.com/yourusername/nexus-x-vpn.git](https://github.com/yourusername/nexus-x-vpn.git)
   cd nexus-x-vpn
