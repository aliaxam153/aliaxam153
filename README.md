<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=2E86C1&center=true&vCenter=true&width=700&lines=Hi+there%2C+I'm+Ali+Azam+%F0%9F%91%8B;MSEE+Researcher+%7C+Embedded+Systems+%7C+Deep+Learning;RFSoC+%7C+GPR+%7C+CycleGAN+%7C+SLAM" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://github.com/aliaxam153">
    <img src="https://komarev.com/ghpvc/?username=aliaxam153&label=Profile%20Views&color=2E86C1&style=flat-square" alt="profile views" />
  </a>
  <img src="https://img.shields.io/badge/Based%20in-Pakistan%20🇵🇰-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Embedded%20RF%20%2B%20Deep%20Learning-2E86C1?style=flat-square" />
</p>

---

## 👨‍🔬 About Me

I'm an **MS Electrical Engineering** student at a research lab in Pakistan, working at the intersection of **embedded RF systems** and **deep learning for subsurface imaging**.

My thesis focuses on building a complete hardware-software stack for a **Stepped-Frequency Continuous Wave (SFCW) Ground Penetrating Radar (GPR)** system — from bare-metal firmware on a Xilinx RFSoC all the way to a CycleGAN-based deep learning pipeline for signal denoising and hyperbola enhancement.

- 🎓 **Thesis:** CycleGAN-Based Ringing Removal & Hyperbola Enhancement Using an RFSoC-Based SFCW GPR System
- 🧑‍🏫 **Supervisor:** Dr. Usman Zabit
- 🔭 **Interests:** Subsurface imaging, radar signal processing, embedded AI, autonomous systems
- 🛠️ **Current Stack:** Xilinx Zynq UltraScale+ ZCU47DR · Yocto/EDF Linux · Python · C/C++

---

## 🧠 Research Focus

```
┌─────────────────────────────────────────────────────────────┐
│                    SFCW GPR System Stack                    │
├─────────────────┬───────────────────┬───────────────────────┤
│  Hardware Layer │   Software Layer  │     AI/ML Layer       │
├─────────────────┼───────────────────┼───────────────────────┤
│ ZCU47DR RFSoC   │ Yocto Embedded    │ CycleGAN (PyTorch)    │
│ LMK04828B Clock │ Linux (EDF/AMD)   │ Unpaired Denoising    │
│ LMK2594 PLL     │ RFDC XCFG Driver  │ Ringing Removal       │
│ SPI/UART/ETH    │ MTS Sync Engine   │ Hyperbola Enhancement │
│ IMU + GPS RTK   │ Python Ctrl Plane │ B-scan Reconstruction │
└─────────────────┴───────────────────┴───────────────────────┘
```

> **Why CycleGAN?** Real-world GPR acquisitions don't come with matched clean/noisy pairs. CycleGAN's unpaired training makes it uniquely suited for field conditions — no synthetic ground truth required.

---

## 🛠️ Tech Stack

### Embedded & Hardware
![Xilinx](https://img.shields.io/badge/Xilinx%20RFSoC-E01F27?style=flat-square&logo=xilinx&logoColor=white)
![Yocto](https://img.shields.io/badge/Yocto%20Linux-4B9CD3?style=flat-square&logo=linux&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![LabVIEW](https://img.shields.io/badge/LabVIEW-FFD700?style=flat-square&logo=ni&logoColor=black)

### AI / Deep Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

### Robotics & Simulation
![ROS](https://img.shields.io/badge/ROS%20Noetic-22314E?style=flat-square&logo=ros&logoColor=white)
![GPRMax](https://img.shields.io/badge/GPRMax-Simulation-orange?style=flat-square)
![WSL2](https://img.shields.io/badge/WSL2-Ubuntu%2020.04-E95420?style=flat-square&logo=ubuntu&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 📌 Featured Projects

### 🛰️ RFSoC-Based SFCW GPR System *(Thesis — Active)*
> Full-stack GPR: firmware → embedded Linux → deep learning pipeline
- Bare-metal SPI driver for **LMK04828B** and **LMK2594** clock ICs on ZCU47DR
- RFDC XCFG driver with **MTS (Multi-Tile Synchronization)** via Ethernet handshaking
- **Yocto/EDF** embedded Linux build for AMD Zynq UltraScale+
- **GPRMax** synthetic B-scan generation for CycleGAN training data
- CycleGAN architecture for **unpaired** ringing removal and target hyperbola enhancement

---

### 🗺️ [ORB-SLAM3 on WSL2 + ROS Noetic](https://github.com/aliaxam153/ORB_SLAM3)
> Modified ORB-SLAM3 for frictionless setup on WSL-2 Ubuntu 20.04 with ROS Noetic integration
- Resolved deprecated dependency conflicts from the original UZ-SLAMLab repository
- Automated **bash-script installer** for Pangolin, OpenCV 4.4.0, ROS Noetic
- Supports **Monocular, Stereo, RGB-D, and Visual-Inertial** configurations
- EuRoC & TUM dataset compatibility with full ROS bag playback support

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aliaxam153&show_icons=true&theme=default&hide_border=true&title_color=2E86C1&icon_color=2E86C1&text_color=333333&bg_color=ffffff" height="165" />
  &nbsp;
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=aliaxam153&theme=default&hide_border=true&ring=2E86C1&fire=2E86C1&currStreakLabel=2E86C1" height="165" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=aliaxam153&theme=flat&no-frame=true&column=6&margin-w=10&title_color=2E86C1" />
</p>

---

## 🔬 Application Domains

| Domain | Relevance |
|---|---|
| 🏗️ Utility Detection | Locate buried pipes & cables before excavation |
| 🧱 Rebar / Structural Inspection | Concrete integrity assessment |
| 💣 Landmine Detection | Humanitarian demining applications |
| 🌱 Precision Agriculture | Soil moisture & root structure mapping |

---

## 📫 Get In Touch

<p align="center">
  <a href="https://github.com/aliaxam153">
    <img src="https://img.shields.io/badge/GitHub-aliaxam153-181717?style=for-the-badge&logo=github" />
  </a>
</p>

<p align="center">
  <i>"The best way to predict the future is to build it — one register at a time."</i>
</p>
