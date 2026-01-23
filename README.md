<div align="center">

# 🎮 Metro Royale Guide

![Flutter Dart](https://img.shields.io/badge/Flutter-Dart-blue?logo=flutter)
![Metro Royale Guide](https://img.shields.io/badge/PUBG_Mobile-Metro_Royale-blue?logo=pubg)
[![Google Play](https://img.shields.io/badge/Google_Play-Download-34A853?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.nithishgajula.guide_for_pubg_metro_royale)
![Platform](https://img.shields.io/badge/platform-Android%20%7C%20iOS%20%7C%20Windows%20%7C%20Linux%20%7C%20macOS-blue?logo=androidstudio&logoColor=white)
<img src="https://img.shields.io/github/downloads/nithish-gajula/MetroRoyaleGuide/total?color=yellow&logo=github" alt="GitHub Release Downloads">
<img src="https://img.shields.io/github/stars/nithish-gajula/MetroRoyaleGuide" alt="GitHub Repo Stars" />

</div>

An application that helps players understand PUBGM Metro Royale through interactive maps and detailed spawn location insights.

## 🚀 Core Features
- **🗺️ Metro Royale Maps**: Arctic Base, Misty Port, Old Blockade Zone, Frontline Confrontation
- **📱 Map Modes**: Basic, Advanced, Radiation
- **🎯 Interactive Spawn Markers**: Squad spawns, solo spawns, special crates, supply crates, weapon crates, file cabinets, password doors, laptops, boss, shops, tank, zombie labs
- **📍 Coordinate System**: Tap-to-get map coordinates (crosshair mode)
- **🖼️ High-Res Zoom**: Double-tap & pinch-to-zoom preview images (16:9)
- **📥 Dynamic Assets**: Download AreaViews on-demand

## 🎨 UI/UX Highlights
- Custom PUBG-Metro style fonts
- Material 3 Dark Theme
- PUBG-style color-coded markers
- Smooth Map InteractiveViewer (zoom 0.5x-4x)
- Bottom sheets with dual Area image previews
- spawn type counters

## 📦 Installation

📱 **Android**: Download from the Google Play Store <a href="https://play.google.com/store/apps/details?id=com.nithishgajula.guide_for_pubg_metro_royale">
    <img src="Misc/get_it_on_google_play.svg" alt="Get it on Google Play" height="30"></a>

#### 🐧 Linux

Linux builds are available in two formats. Choose the one that suits you best.
Release version: <a href="https://github.com/nithish-gajula/MetroRoyaleGuide/releases/tag/v2.6.0">v2.6.0</a>


###### Linux AppImage Setup

1. Download `Metro_Royale_Guide-Linux-x86_64.AppImage` from the <a href="https://github.com/nithish-gajula/MetroRoyaleGuide/releases/tag/v2.6.0">releases</a>
2. Make the AppImage executable: `chmod +x Metro_Royale_Guide-Linux-x86_64.AppImage`
3. Run the app: `./Metro_Royale_Guide-Linux-x86_64.AppImage`

###### Linux tar.gz Archive Setup

1. Download `MetroRoyaleGuide-Linux-x64.tar.gz` from the <a href="https://github.com/nithish-gajula/MetroRoyaleGuide/releases/tag/v2.6.0">releases</a>
2. Untar the file `tar -xvzf MetroRoyaleGuide-Linux-x64.tar.gz`
3. Make the binary executable (if not) `chmod +x bundle/guide_for_pubg_metro_royale`
4. Run `./bundle/guide_for_pubg_metro_royale`

#### 🖥️ Windows

Windows builds are coming soon 🚧
They will be published in the <a href="https://github.com/nithish-gajula/MetroRoyaleGuide/releases/tag/v2.6.0">releases</a> section once available.

## 🚉 Metro Royale Guide – Static Assets

This repository contains **static assets** used by the <a href="https://github.com/nithish-gajula/MetroRoyaleGuide">metro royale guide</a> application, including **spawn icons** and **map images**.

> [!IMPORTANT]
> These assets are intended for **informational and guide purposes only**.  
> This is a **fan-made project** and is not affiliated with or endorsed by the official game developers.


### ⚜️ Spawn Icons

The app supports multiple **spawn types**, each represented by a dedicated icon.  
These icons are used across **Filter Chips** and **Spawn Markers** in the app UI.

### 💢 Spawn Types

1. **Supply Crates**  
   - Normal  
     <img src="SpawnIcons/supply_crate.png" width="48" alt="Supply Crate">  
   - Rich  
     <img src="SpawnIcons/supply_crate_special.png" width="48" alt="Supply Crate Special">

2. **Weapon Crates**  
   <img src="SpawnIcons/weapon_crate.png" width="48" alt="Weapon Crate">

3. **File Cabinets**  
   <img src="SpawnIcons/file_cabinet.png" width="48" alt="File Cabinet">


4. **Special Crates**  
   <img src="SpawnIcons/special_crate.png" width="48" alt="Special Crate">

5. **Password Doors**  
   <img src="SpawnIcons/password_door.png" width="48" alt="Password Door">

6. **Zombie Labs**  
   <img src="SpawnIcons/zombie_lab.png" width="48" alt="Zombie Lab">

7. **Shops**  
   <img src="SpawnIcons/shop.png" width="48" alt="Shop">

8. **Laptops**  
   <img src="SpawnIcons/laptop.png" width="48" alt="Laptop">

9. **Bosses**  
   <img src="SpawnIcons/boss.png" width="48" alt="Boss">

10. **Solo Spawns**  
    - Normal  
      <img src="SpawnIcons/solo.png" width="48" alt="Solo Spawn">  
    - Rich  
      <img src="SpawnIcons/solo_special.png" width="48" alt="Solo Spawn Rare">

11. **Squad Spawns**  
    - Normal  
      <img src="SpawnIcons/squad.png" width="48" alt="Squad Spawn">  
    - Rich  
      <img src="SpawnIcons/squad_special.png" width="48" alt="Squad Spawn Rare">


### 📐 Spawn Icon Specifications

- **Dimensions:** 128 × 128 px  
- **Format:** PNG  
- **Average Size:** ~50 KB  


## 🗺️ Maps

The Metro Royale mode includes **6 playable maps**, each supporting one or more game modes.

### 🧭 Available Maps & Modes

1. **Frontline Confrontation**  
   - Basic

2. **Old Blockade Zone**  
   - Basic  
   - Advanced  
   - Radiation

3. **Misty Port**  
   - Basic  
   - Advanced  
   - Radiation

4. **Arctic Base**  
   - Basic  
   - Advanced  
   - Radiation

5. **Zombie Uprising 2.0**  
   - Advanced

6. **Survival Drop**  
   - Advanced


## 📏 Map Asset Specifications

#### Mini Maps
- **Dimensions:** 512 × 512 px *(currently unclassified)*  
- **Format:** JPG / JPEG  
- **File Size:** < 1 MB  

#### Large Maps
- **Dimensions:** 1024 × 1024 px  
- **Format:** JPG / JPEG  
- **File Size:** < 2 MB  


## 📌 Notes

- Assets are optimized for **performance and clarity** on mobile devices  
- Map images are designed for **interactive overlays and zooming**
- File sizes are kept minimal to reduce memory usage


## 📝 License

Copyright © 2026 **Nithish Gajula**. All rights reserved.  

This software and its source code are **proprietary** and **confidential**.  
Unauthorized copying, modification, distribution, or use of this software, via any medium, is strictly prohibited.
Reverse engineering, decompiling, or disassembling the software is prohibited to the maximum extent permitted by law.

## 🤝 Support & Connect

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.nithishgajula.guide_for_pubg_metro_royale">
    <img src="Misc/get_it_on_google_play.svg" alt="Get it on Google Play" height="60">
  </a>
</p>

<div align="center">

Built with ❤️ by [Nithish Gajula](https://github.com/nithish-gajula) — 🎮 for **Metro Royale** fans.

**⭐ Star the repository if you find it useful!**

[![Play Console Profile](https://img.shields.io/badge/Play_Console-blue?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/dev?id=6041690382423833029)
[![Developer Site](https://img.shields.io/badge/Portfolio-255E63?logo=About.me&logoColor=white)](https://nithish-gajula.github.io)
[![Email](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white)](mailto:gajulanithish000@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nithish-gajula-90130b227)
[![X](https://img.shields.io/badge/-000?logo=x&logoColor=white)](https://x.com/gajula_nithish)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white)](https://www.instagram.com/nithish_gajula)


</div>