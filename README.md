# 🔄 Temp Hardware Spoofer [![License](https://img.shields.io/badge/License-BSD_3--Clause-Blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

A stealthy hardware identity cycler for Windows 10/11, designed for temporary bypass of gaming platform restrictions.  
**"New hardware fingerprint on every boot"** 🔄

![Spoofer Demo](https://github.com/user-attachments/assets/d7cf0bb7-0844-4a59-9764-23449bb4b7c9)  
*(Replace with actual animated demo GIF)*

## 🚨 Red Alert: Critical Disclaimer
<div align="center">
  <img src="https://img.icons8.com/color/48/000000/warning-shield.png" width="30"/>
  <strong>This is NOT a magic bullet!</strong>
</div>

- ⚖️ **Legal Notice**: Violates most EULAs - Use at **YOUR OWN RISK**
- 💀 **Consequences**: Permanent game/account bans possible
- 🎓 **Intended Use**: Academic research on hardware identification systems

## 🌟 Featured Capabilities
### 🔧 Core Functionality
- ⌛ Ephemeral Spoofing - No persistent registry changes
- ♻️ Auto-Cycle - Fresh fingerprint on each system restart
- 🧹 Clean Uninstall - Zero residual traces

### 🎮 Supported Platforms
![Vanguard](https://img.shields.io/badge/Riot_Vanguard-FF0000?style=flat&logo=riotgames&logoColor=white)
![BattlEye](https://img.shields.io/badge/BattlEye-000000?style=flat)
![EasyAntiCheat](https://img.shields.io/badge/EAC-121212?style=flat&logo=easylinux&logoColor=white)

### 🖥️ Hardware Profile Rotation
| Component       | Spoofed Identifiers                |
|-----------------|-------------------------------------|
| Motherboard     | Serial, UUID, Model                 |
| Storage         | Drive Serial, HDD/SSD IDs           |
| Network         | MAC Address, Adapter Configuration  |
| GPU             | Device ID, BIOS Version             |

## 🛠️ Installation & Operation
```bash
# Clone Repository
git clone https://github.com/yourusername/temp-hardware-spoofer.git
cd temp-hardware-spoofer

# Initialize Environment
spoiler init --env=prod --mode=stealth

# Launch Spoofer
start /MIN Spoofer.exe --cycle --clean
