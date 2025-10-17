<!-- PROJECT HEADER -->
<h1 align="center">⚡ CustomRP MatrixPresence</h1>

<p align="center">
  <strong>A professional and customizable Discord Rich Presence preset system</strong><br>
  Designed, documented, and maintained by <a href="https://github.com/power0matin"><strong>@power0matin</strong></a>
</p>

<p align="center">
  <a href="https://discord.com/developers/applications/">
    <img alt="Discord Developer Portal" src="https://img.shields.io/badge/Discord-Developer%20Portal-5865F2?logo=discord&logoColor=white&style=for-the-badge">
  </a>
  <a href="https://github.com/maximmax42/Discord-CustomRP">
    <img alt="CustomRP Project" src="https://img.shields.io/badge/CustomRP-Project-000000?logo=github&logoColor=white&style=for-the-badge">
  </a>
  <a href="https://github.com/power0matin/CustomRP-MatrixPresence/releases">
    <img alt="Release" src="https://img.shields.io/github/v/release/power0matin/CustomRP-MatrixPresence?style=for-the-badge&color=brightgreen">
  </a>
  <a href="LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge">
  </a>
</p>


## 🧩 Overview

**MatrixPresence** is a clean, reusable preset system for [CustomRP](https://github.com/maximmax42/Discord-CustomRP)  
It helps creators, developers, and sellers build **professional and brand-ready Discord Rich Presences** — fast.

### ✨ Key Features
- 🖼️ Support for large and small image assets  
- 🔗 Two customizable HTTPS buttons (e.g., *Store* / *Support*)  
- 🕓 Optional live timestamp  
- 🧾 Fully documented XML configuration  
- 💡 Developer-friendly structure and comments  


## 🚀 Quick Start

1. **Create a Discord Application** via the [Developer Portal](https://discord.com/developers/applications/).  
2. Copy your **Application ID**.  
3. Upload your images under **Rich Presence → Art Assets** (e.g., `large_image_key`, `small_image_key`).  
4. Open [`/presets/CustomRP_Sample_Preset.xml`](presets/CustomRP_Sample_Preset.xml) and edit:
   - Replace `YOUR_APP_ID`
   - Update image keys (`large_image_key`, `small_image_key`)
   - Add your own button URLs  
5. In **CustomRP**, go to:

File → Load preset → Select the XML file

Then click **Connect → Update Presence**.


## 🛠️ Troubleshooting

### Buttons not showing?
- ✅ Use **HTTPS** links only  
- ✅ Ensure you’re using **your own** Application ID  
- ✅ After editing, click **Disconnect → Connect → Update Presence**  
- 🔄 If still missing, reload Discord (`Ctrl + R`)

### Images not rendering?
- `LargeKey` and `SmallKey` **must match** your uploaded Art Asset names exactly  
- Only **PNG** and **JPG** formats are supported (GIFs not allowed)


## 📂 Repository Structure

```
CustomRP-MatrixPresence/
├── presets/
│   └── CustomRP_Sample_Preset.xml   # Fully commented XML template
├── .gitignore
├── .gitattributes
├── LICENSE
└── README.md
```


## 👨‍💻 Author

Created and maintained by [**@power0matin**](https://github.com/power0matin)  
> “Building clean, modular, and visually consistent systems for Discord creators.”

If you find this useful, please ⭐ **star the repo** to show your support!


## 🔗 Useful Links
- 🧭 **Discord Developer Portal:** [discord.com/developers/applications](https://discord.com/developers/applications/)  
- 💻 **CustomRP GitHub Project:** [github.com/maximmax42/Discord-CustomRP](https://github.com/maximmax42/Discord-CustomRP)  
- 🌐 **MatrixPresence Repository:** [github.com/power0matin/CustomRP-MatrixPresence](https://github.com/power0matin/CustomRP-MatrixPresence)


## 📄 License
Released under the **MIT License** — see [`LICENSE`](LICENSE) for details.  
You are free to use, modify, and share this project with proper credit.


<p align="center">
  <sub>© 2025 power0matin — All rights reserved.</sub>
</p>
