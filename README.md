<div align="center">

<!-- Animated banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1a3a5c,100:2E86C1&height=200&section=header&text=Ali%20Azam&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=MSEE%20Researcher%20%7C%20Embedded%20RF%20%7C%20Deep%20Learning&descAlignY=58&descSize=18&animation=fadeIn" />

<!-- Animated typing -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=3000&pause=800&color=2E86C1&center=true&vCenter=true&width=650&lines=Building+hardware+%E2%86%92+firmware+%E2%86%92+deep+learning;RFSoC+%7C+Yocto+Linux+%7C+CycleGAN+%7C+GPR;Subsurface+Imaging+meets+Embedded+AI;Check+out+my+YouTube+%40albazishere!" alt="Typing SVG" />

<br/>

<a href="https://github.com/aliaxam153">
  <img src="https://komarev.com/ghpvc/?username=aliaxam153&label=Profile+Views&color=2E86C1&style=for-the-badge" />
</a>
&nbsp;
<img src="https://img.shields.io/badge/Pakistan-%F0%9F%87%B5%F0%9F%87%B0-1a3a5c?style=for-the-badge" />
&nbsp;
<img src="https://img.shields.io/badge/Status-Research%20Active-2E86C1?style=for-the-badge&logo=statuspage&logoColor=white" />

</div>

<br/>

---

## ⚡ About Me

I'm an **MS Electrical Engineering** researcher in Pakistan, working at the intersection of **embedded RF systems** and **deep learning for subsurface imaging**. My thesis constructs an end-to-end hardware-software stack for a **Stepped-Frequency Continuous Wave (SFCW) Ground Penetrating Radar** — from bare-metal RFSoC firmware through Yocto embedded Linux, up to a CycleGAN-based AI pipeline for signal denoising and target enhancement.

| | |
|---|---|
| 🎓 **Thesis** | CycleGAN-Based Ringing Removal & Hyperbola Enhancement Using an RFSoC-Based SFCW GPR System |
| 🧑‍🏫 **Supervisor** | Dr. Usman Zabit |
| 🔭 **Interests** | Radar signal processing · Subsurface imaging · Embedded AI · Autonomous SLAM |
| 🛠️ **Current Stack** | Zynq UltraScale+ ZCU47DR · Yocto/EDF · Python · C/C++ |

---

## 🧠 Research Stack

```
╔══════════════════════════╦═══════════════════════╦══════════════════════════╗
║     Hardware Layer       ║    Software Layer     ║       AI / ML Layer      ║
╠══════════════════════════╬═══════════════════════╬══════════════════════════╣
║  ZCU47DR RFSoC           ║  Yocto / EDF Linux    ║  CycleGAN (PyTorch)      ║
║  LMK04828B Clock IC      ║  RFDC XCFG Driver     ║  Unpaired Denoising      ║
║  LMK2594 PLL Synthesizer ║  MTS Sync (Ethernet)  ║  Ringing Removal         ║
║  SPI / UART / Ethernet   ║  Python Control Plane ║  Hyperbola Enhancement   ║
║  IMU + GPS RTK (UM982)   ║  GPRMax Simulation    ║  B-scan Reconstruction   ║
╚══════════════════════════╩═══════════════════════╩══════════════════════════╝
```

> 💡 **Why CycleGAN?** Real-world GPR acquisitions lack matched clean/noisy pairs. CycleGAN's unpaired training makes it uniquely suited for field deployment — no synthetic ground truth required.

---

## 🛠️ Tech Stack

<div align="center">

**Embedded & Hardware**

![Xilinx](https://img.shields.io/badge/Xilinx%20RFSoC-E01F27?style=for-the-badge&logo=xilinx&logoColor=white)
![Yocto](https://img.shields.io/badge/Yocto%20Linux-4B9CD3?style=for-the-badge&logo=linux&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![LabVIEW](https://img.shields.io/badge/LabVIEW-FFD700?style=for-the-badge&logo=ni&logoColor=black)

**AI / Deep Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

**Robotics & Simulation**

![ROS](https://img.shields.io/badge/ROS%20Noetic-22314E?style=for-the-badge&logo=ros&logoColor=white)
![GPRMax](https://img.shields.io/badge/GPRMax-Simulation-FF6B35?style=for-the-badge)
![Ubuntu](https://img.shields.io/badge/WSL2%20Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📌 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛰️ RFSoC-Based SFCW GPR System
**`Thesis — Active`**

Full-stack GPR: bare-metal firmware → Yocto embedded Linux → CycleGAN deep learning pipeline.

- SPI driver for **LMK04828B** & **LMK2594** clock ICs
- RFDC XCFG driver with **MTS sync** via Ethernet
- **Yocto/EDF** Linux build for AMD Zynq UltraScale+
- **GPRMax** synthetic B-scan generation
- CycleGAN unpaired ringing removal & hyperbola enhancement

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![C](https://img.shields.io/badge/-C-00599C?style=flat-square&logo=c&logoColor=white)
![Yocto](https://img.shields.io/badge/-Yocto-4B9CD3?style=flat-square&logo=linux&logoColor=white)

</td>
<td width="50%" valign="top">

### 🗺️ [ORB-SLAM3 on WSL2 + ROS Noetic](https://github.com/aliaxam153/ORB_SLAM3)

Modified ORB-SLAM3 for frictionless setup on WSL-2 Ubuntu 20.04 with full ROS Noetic integration.

- Resolved deprecated dependency conflicts from original UZ-SLAMLab repo
- Automated **bash-script installer** for Pangolin, OpenCV 4.4.0, ROS Noetic
- Supports **Monocular, Stereo, RGB-D & Visual-Inertial** configs
- EuRoC & TUM dataset compatibility with ROS bag playback

![ROS](https://img.shields.io/badge/-ROS%20Noetic-22314E?style=flat-square&logo=ros&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Ubuntu](https://img.shields.io/badge/-Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

</td>
</tr>
</table>

---

## 🔬 Application Domains

<div align="center">

| Domain | Application |
|:---:|:---|
| 🏗️ **Utility Detection** | Locate buried pipes & cables non-destructively before excavation |
| 🧱 **Structural Inspection** | Rebar mapping & concrete integrity assessment |
| 💣 **Landmine Detection** | Humanitarian demining in post-conflict zones |
| 🌱 **Precision Agriculture** | Soil moisture profiling & root structure mapping |

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=aliaxam153&show_icons=true&theme=tokyonight&hide_border=true&title_color=2E86C1&icon_color=2E86C1&bg_color=0D1117&text_color=c9d1d9" height="170" />
&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=aliaxam153&theme=tokyonight&hide_border=true&ring=2E86C1&fire=FF6B35&currStreakLabel=2E86C1&background=0D1117&sideLabels=c9d1d9&dates=c9d1d9" height="170" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=aliaxam153&theme=tokyonight&no-frame=true&column=6&margin-w=10" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=aliaxam153&bg_color=0D1117&color=2E86C1&line=2E86C1&point=FF6B35&area=true&hide_border=true" />

</div>

---

## 📺 YouTube Channel

<div align="center">

<a href="https://www.youtube.com/@albazishere">
  <img src="https://img.shields.io/badge/YouTube-%40albazishere-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
</a>

</div>

> 🎬 Follow along on **[@albazishere](https://www.youtube.com/@albazishere)** — tutorials, project walkthroughs, and technical deep-dives on embedded systems, radar, and deep learning.

---

## 🤝 Connect With Me

<div align="center">

<a href="https://github.com/aliaxam153">
  <img src="https://img.shields.io/badge/GitHub-aliaxam153-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
&nbsp;
<a href="https://www.youtube.com/@albazishere">
  <img src="https://img.shields.io/badge/YouTube-albazishere-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
</a>
&nbsp;
<a href="https://www.credly.com/users/ali-azam.2fde4faa/badges">
  <img src="https://img.shields.io/badge/Credly-Verified%20Badges-FF6B35?style=for-the-badge&logo=credly&logoColor=white" />
</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E86C1,50:1a3a5c,100:0D1117&height=120&section=footer&animation=fadeIn" />

</div>
