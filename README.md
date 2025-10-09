# Text Forge Mode Library
Modes status overview for official [Text Forge](https://github.com/mkh-user/text-forge) mods

## "Mode" concept in Text Forge
Text Forge designed to be lightweight and modular, so we use language agnostic development to keep it in this frame and have highly extendable architecture. To support save/load buffers, syntax highlighters, and every special feature for every file and format, Text Forge provides "Modes". A mode is a module with all data related to a language, framework or file type. With text-based and object oriented design modes can have very small size. (currently less than 10KB for each official mode)

## About TFM API
Text Forge have a powerful API for modes based on GDScript, this API name is **Text Forge Mode API** (TFM API in short). This API received some major updates and currently haven't complete support for older API versions, so we use TFM API badge to define mode supporting level. You can use just a mode with same API major version number as your editor internal API. Minor API version updates may have little breaking features or simple added features. Using latest editor for latest TFM API and new feature and fixes (specialy for modes) is very recommended. Currenlty latest version is v2.1. (All `a.x` versions are backward compatible down to version `a.y` if `x` > `y`)

# Mode support status

Click on mode name to navigate to its source repo.

### Modes Count: 11
### Available Extensions: 23

### Types:
🎖️ Official (and community) - 👥 Community
### Features:
🎨 Syntax Highlighter - 🗂️ Mode Panel - 🪄 Auto Format - 📐 Auto Indent - ⚡ Code Completion - 🖼️ Preview - 🧭 Outline - 🚨 Linting
### Other Flags:
🗃️(Before name) Mode kit - 🧪(With note) Experimental - 🚧 Updating... - 🧾 Custom File Encoding - 🕸️(Section with API version) Outdated

> List is sorted in a to z order. Mode kits are above modes.
> <!--Order: A B C D E F G H I J K L M N O P Q R S T U V W X Y Z-->

---

### 🗃️ [Web](https://github.com/text-forge/web-mode-kit) 🎖️🎨🪄⚡🧭 (HTML, CSS, JavaScript, Markdown, JSON)
### [GDScript](https://github.com/text-forge/gdscript-mode) 🎖️🎨🪄⚡🧭
### [CSS](https://github.com/text-forge/web-mode-kit) 🎖️🎨⚡
### [CSV](https://github.com/text-forge/csv-mode) 🎖️🎨🖼️🧭🚨
### [HTML](https://github.com/text-forge/web-mode-kit) 🎖️🎨🪄⚡🧭
### [INI](https://github.com/text-forge/ini-mode) 🎖️🎨🪄🧭
### [JavaScript](https://github.com/text-forge/web-mode-kit) 🎖️🎨⚡
### [JSON](https://github.com/text-forge/web-mode-kit) 🎖️🎨🪄
### [Markdown](https://github.com/text-forge/web-mode-kit) 🎖️🎨🧭
### [Python](https://github.com/text-forge/python-mode) 🎖️🎨🗂️⚡🧭🧪
> 🧪 With an experimental run code feature
### [Rust](https://github.com/text-forge/rust-mode) 🎖️🎨⚡
### [SVG](https://github.com/text-forge/svg-mode) 🎖️🎨🪄⚡🖼️🧭

---
### 🕸️ Text Forge Mode API v1.0
#### 🗃️ [Standard Mode Kit](https://github.com/text-forge/mode-library/tree/mode-api-1) 🎖️🎨🧹

---

# Contribute
- Please open an issue for each mode/mode kit you want to add, it can be your mode or a mode created by someone else.
- Describe mode features and provide link to mode source. 
- For mode kits, describe that kit contents can be used separately or no. These mode kits should provide `.tfmode` for each mode separately (and one for full kit) in releases. 
- Please use template in mode README file (see official modes/mode kits for example) and add `text-forge` tag to source repo, or recommend these changes to mode maintainers.
