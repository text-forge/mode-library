# Text Forge Modes
Modes overview for official [Text Forge](https://github.com/mkh-user/text-forge) mods

## "Mode" concept in Text Forge
Text Forge designed to be lightweight and modular, so we use language agnostic development to keep it in this frame and have highly extendable architecture. To support save/load buffers, syntax highlighters, and every special feature for every file and format, Text Forge provides "Modes". A mode is a module with all data related to a language, framework or file type. With text-based and object oriented design modes can have very small size. (currently less than 10KB for each official mode)

## About TFM API
Text Forge have a powerful API for modes based on GDScript, this API name is **Text Forge Mode API** (TFM API in short). This API received some major updates and currently haven't complete support for older API versions, so we use TFM API badge to define mode supporting level. You can use just a mode with same API major version number as your editor internal API. Minor API version updates may have little breaking features or simple added features. Using latest editor for latest TFM API and new feature and fixes (specialy for modes) is very recommended.

# Mode support status

Click on mode name to navigate to its source repo.

### Types:
🎖️ Official (and community) - 👥 Community
### Features:
🎨 Syntax Highlighter - 🗂️ Mode Panel - 🧹 Auto Format - 📐 Auto Indent - ⚡ Code Completion - 🖼️ Preview - 🧭 Outline - 🚨 Linting
### Other Flags:
🗃️(Before name) Mode kit - 🧪(With note) Experimental - 🚧 Update in progress - 🧾 Custom File Encoding - 🕸️(Section with API version) Outdated

> List is sorted in a to z order. Mode kits are above modes.

---

### 🗃️ [Web](https://github.com/text-forge/web-mode-kit) 🎖️🎨🧹⚡🧪
> 🧪 HTML is supported, but other modes are in progress
### [GDScript](https://github.com/text-forge/gdscript-mode) 🎖️🎨⚡🧭
### [Python](https://github.com/mkh-user/text-forge-python-mode) 👥🎨🗂️⚡🧭🧪
> 🧪 With an experimental run code feature

---
### 🕸️ Text Forge Mode API v1.0
#### 🗃️ [Standard Mode Kit](https://github.com/text-forge/mode-library/tree/mode-api-1) 🎖️🎨🧹