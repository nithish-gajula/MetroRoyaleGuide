<div align="center">

# 🎮 Metro Royale Guide

![Flutter Dart](https://img.shields.io/badge/Flutter-Dart-blue?logo=flutter)
![Metro Royale Guide](https://img.shields.io/badge/PUBG_Mobile-Metro_Royale-blue?logo=pubg)
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

📱 **Android**: Download from the Google Play Store &nbsp;&nbsp; [![Google Play](https://img.shields.io/badge/Google_Play-Download-34A853?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.nithishgajula.guide_for_pubg_metro_royale)

#### 🐧 Linux

Linux builds are available in two formats. Choose the one that suits you best.
Release version: <a href="https://github.com/nithish-gajula/MetroRoyaleGuide/releases/tag/v2.7.0">v2.7.0</a>


###### Linux AppImage Setup

1. Download `Metro_Royale_Guide-Linux-x86_64.AppImage` from the <a href="https://github.com/nithish-gajula/MetroRoyaleGuide/releases/tag/v2.7.0">releases</a>
2. Make the AppImage executable: `chmod +x Metro_Royale_Guide-Linux-x86_64.AppImage`
3. Run the app: `./Metro_Royale_Guide-Linux-x86_64.AppImage`

###### Linux tar.gz Archive Setup

1. Download `MetroRoyaleGuide-Linux.tar.gz` from the <a href="https://github.com/nithish-gajula/MetroRoyaleGuide/releases/tag/v2.7.0">releases</a>
2. Untar the file `tar -xzvf MetroRoyaleGuide-Linux.tar.gz`
3. Go to cd bundle directory `cd MetroRoyaleGuide/bundle/`
3. Make the binary executable (if not) `chmod +x guide_for_pubg_metro_royale`
4. Run `./guide_for_pubg_metro_royale`

#### 🖥️ Windows

Windows builds are coming soon 🚧
They will be published in the <a href="https://github.com/nithish-gajula/MetroRoyaleGuide/releases/tag/v2.7.0">releases</a> section once available.

## 🚉 Metro Royale Guide – Static Assets

This repository contains **static assets** used by the <a href="https://github.com/nithish-gajula/MetroRoyaleGuide">metro royale guide</a> application, including **spawn icons** and **map images**.

> [!IMPORTANT]
> These assets are intended for **informational and guide purposes only**.  
> This is an **unofficial, fan-made project** and is not affiliated with or endorsed by the official game developers.


### ⚜️ Spawn Icons

The app supports multiple **spawn types**, each represented by a dedicated icon.  
These icons are used across **Filter Chips** and **Spawn Markers** in the app UI.

### 💢 Spawn Types

| Spawn Type         | Variants        | Icon |
| :------------------| :---------------| :---: |
| **Supply Crates**  | Standard & Rich  | <img src="SpawnIcons/supply_crate.png" width="40"> <img src="SpawnIcons/supply_crate_special.png" width="40"> |
| **Weapon Crates**  | Standard        | <img src="SpawnIcons/weapon_crate.png" width="40"> |
| **File Cabinets**  | Standard        | <img src="SpawnIcons/file_cabinet.png" width="40"> |
| **Special Crates** | Standard        | <img src="SpawnIcons/special_crate.png" width="40"> |
| **Password Doors** | Standard        | <img src="SpawnIcons/password_door.png" width="40"> |
| **Zombie Labs**    | Standard        | <img src="SpawnIcons/zombie_lab.png" width="40"> |
| **Shops**          | Standard        | <img src="SpawnIcons/shop.png" width="40"> |
| **Laptops**        | Standard        | <img src="SpawnIcons/laptop.png" width="40"> |
| **Bosses**         | Standard        | <img src="SpawnIcons/boss.png" width="40"> |
| **Solo Spawns**    | Standard & Rare  | <img src="SpawnIcons/solo.png" width="40"> <img src="SpawnIcons/solo_special.png" width="40"> |
| **Squad Spawns**   | Standard & Rare  | <img src="SpawnIcons/squad.png" width="40"> <img src="SpawnIcons/squad_special.png" width="40"> |


## 🗺️ Maps

The Metro Royale mode includes **6 playable maps**, each supporting one or more game modes.

### 🧭 Available Maps & Modes


<table>
  <thead>
    <tr>
      <th>#</th>
      <th>Map Name</th>
      <th colspan="3", align="left">Available Modes (🟢Basic, 🟣Advanced, ☢️Radiation)</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>1</td>
      <td align="left"><strong>Frontline Confrontation</strong></td>
      <td>Basic</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr align="center">
      <td>2</td>
      <td align="left"><strong>Old Blockade Zone</strong></td>
      <td>Basic</td>
      <td>Advanced</td>
      <td>Radiation</td>
    </tr>
    <tr align="center">
      <td>3</td>
      <td align="left"><strong>Misty Port</strong></td>
      <td>Basic</td>
      <td>Advanced</td>
      <td>Radiation</td>
    </tr>
    <tr align="center">
      <td>4</td>
      <td align="left"><strong>Arctic Base</strong></td>
      <td>Basic</td>
      <td>Advanced</td>
      <td>Radiation</td>
    </tr>
    <tr align="center">
      <td>5</td>
      <td align="left"><strong>Zombie Uprising 2.0</strong></td>
      <td>-</td>
      <td>Advanced</td>
      <td>Radiation</td>
    </tr>
    <tr align="center">
      <td>6</td>
      <td align="left"><strong>Survival Drop</strong></td>
      <td>-</td>
      <td>Advanced</td>
      <td>Radiation</td>
    </tr>
  </tbody>
</table>


## 📌 Notes

- Assets are optimized for **performance and clarity** on mobile devices  
- Map images are designed for **interactive overlays and zooming**
- File sizes are kept minimal to reduce memory usage


## 📐 Asset Specifications


| Map Type        | Dimensions      | Format       | File Size |
| :---------------| :---------------| :------------| :---------|
| **Spawn Icons** | 128 × 128 px    | PNG          | ~ 50 Kb   |
| **Mini Maps**   | 512 × 512 px    | JPG / JPEG   | < 1 MB    |
| **Large Maps**  | 1024 × 1024 px  | JPG / JPEG   | < 2 MB    |




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