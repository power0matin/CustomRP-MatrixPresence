# CustomRP MatrixPresence

A clean, reusable preset system for **Discord Rich Presence** powered by [CustomRP](https://github.com/maximmax42/Discord-CustomRP).  
Curated and maintained by **[@power0matin](https://github.com/power0matin)**.

<p align="left">
  <a href="https://discord.com/developers/applications/"><img alt="Discord Developer Portal" src="https://img.shields.io/badge/Discord-Developer%20Portal-5865F2?logo=discord&logoColor=white"></a>
  <a href="https://github.com/maximmax42/Discord-CustomRP"><img alt="CustomRP" src="https://img.shields.io/badge/CustomRP-Project-000000?logo=github&logoColor=white"></a>
  <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-green.svg"></a>
</p>

## What is this?

**MatrixPresence** is a minimal, documented set of **XML presets** for CustomRP.  
It’s perfect when you want a professional, brandable **Rich Presence** with:

- Large & small image assets
- Two HTTPS buttons (e.g., Store / Support)
- Optional live timestamp
- Clear comments and placeholders

## Quick Start

1. **Create an app** in the [Discord Developer Portal](https://discord.com/developers/applications/).
2. Copy the **Application ID**.
3. Upload your images at **Rich Presence → Art Assets** (e.g., `large_image_key`, `small_image_key`).
4. Open [`/presets/CustomRP_Sample_Preset.xml`](presets/CustomRP_Sample_Preset.xml) and replace placeholders:
   - `YOUR_APP_ID`
   - `large_image_key`, `small_image_key`
   - Example button URLs
5. In CustomRP: **File → Load preset… → select the XML**, then **Connect → Update Presence**.

## Troubleshooting

- **Buttons don’t show up**

  - Use **HTTPS** links only.
  - Make sure you’re using **your own** Application ID.
  - After changes: **Disconnect → Connect → Update Presence**, then reload Discord (`Ctrl+R`).

- **Images don’t render**
  - `LargeKey` / `SmallKey` must exactly match **Art Asset keys** in your application.
  - Use static PNG/JPG files (GIFs won’t work here).

## Repo Structure

```
presets/
  └─ CustomRP_Sample_Preset.xml   # Fully commented template
.gitignore
.gitattributes
LICENSE
README.md
```

## Author

Built and maintained by **[@power0matin](https://github.com/power0matin)**.  
If this helps you, consider starring the repo ⭐

## Useful Links

- Discord Developer Portal → https://discord.com/developers/applications/
- CustomRP project → https://github.com/maximmax42/Discord-CustomRP

## License

Released under the **MIT License**. See [`LICENSE`](LICENSE).
