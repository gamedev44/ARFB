# Action Recorder for Blender (ARFB)

> A port of the Bubblebath Engine Action Recorder—making animations and actions easier than ever before.  
> Designed to work in conjunction with **RFBE** (RiskFlip Blender Edition, aka rIFK fLIP).

## 📑 Table of Contents

- [⚙️ Features](#️-features)
- [🎯 Requirements](#🎯-requirements)
- [🚀 Installation](#🚀-installation)
- [📖 Usage](#📖-usage)
- [🔗 Related](#🔗-related)
- [📄 License](#📄-license)

## ⚙️ Features

- **Live transform capture**: record location, rotation, scale in real time  
- **Pause & advance**: control how many frames to pause before advancing  
- **Frequency controls**: adjust keyframe spacing per channel (L/R/S)  
- **Time-scrub selection**: select/deselect/delete keyframes by dragging the time slider  
- **Keyframe info**: see which channels have keyframes under the playhead  
- **Smooth-follow mode**: make objects follow your cursor with adjustable speed  

## 🎯 Requirements

- Blender 3.6.2  
- Python 3.8+ (bundled with Blender)  

## 🚀 Installation

1. Visit the [Newest Release](https://github.com/gamedev44/ARFB/releases) and download the latest `.zip`.  
2. In Blender: **Edit → Preferences → Add-ons → Install…**  
3. Select the downloaded file and enable **Action Recorder**.  


## 📖 Usage

1. Switch to the **Dope Sheet → Action Editor**.  
2. Open the **Sidebar (N-panel) → Animation → Action Recorder**.  
3. Select any object or pose bone.  
4. Hit:
   - **L** to record Location  
   - **R** to record Rotation  
   - **S** to record Scale  
5. Adjust “Pause” and L/R/S frequency sliders as needed.  
6. Scrub the timeline to select/deselect/delete keyframes.  
7. Use **Keyframe Info** to display active channels at the current frame.  
8. Hold **Ctrl** and click **Smooth Follow** to toggle mesh following.  

## 🔗 Related

- **RFBE (RiskFlip Blender Edition)**: workflow-boosting bubblebath-style animation tools.  
- **Bubblebath Engine**: original Action Recorder inspiration.

## 📄 License

Apache License 2.0  
© 2025 IronWill Interactive / Asterisk
