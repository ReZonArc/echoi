<p align="center">
  <img width="160" src="./website/static/readme/noi.png" />
  <p align="center">🚀 Power Your World with AI - Explore, Extend, Empower.</p>
</h2>

[![echoi downloads](https://img.shields.io/github/downloads/ReZonArc/echoi/total.svg?style=flat)](https://github.com/ReZonArc/echoi/releases)



> [!NOTE]
> When installing for the first time, the **echoi Extensions** might not be the latest version. You will need to manually update the extensions from [ReZonArc/echoi/extensions](https://github.com/ReZonArc/echoi/tree/main/extensions) to your computer.
>
> You can locate this option in the settings or open the local extensions directory via the menu: **Help -> echoi UserData -> Extensions**.
>
> ![](./website/static/readme/noi-extensions.png)

## 🔥 Feature

Introducing echoi: an AI-enhanced, customizable browser designed to streamline your digital experience:

**AI Support: [ChatGPT](https://chatgpt.com), [Claude](https://claude.ai), [Gemini](https://gemini.google.com), [Grok](https://grok.com), [DeepSeek](https://chat.deepseek.com), [GitHub Copilot](https://github.com/copilot), [HuggingChat](https://huggingface.co/chat), and more.**

- **Browser**: echoi not only includes curated AI websites but also allows the addition of any URL, providing a tailored browsing experience ([echoi Configs](./configs)).
- **Prompts Management**: Offers robust customization options including the addition, synchronization, batch tagging, and removal of prompts.
- **Noi Ask**: Enables sending batch messages to multiple AI chats, streamlining the process of interacting with various AI services simultaneously ([echoi Extensions](./extensions)). Entries made via Noi Ask are stored locally, ensuring easy access for future review or bookmarking.
- **Themes**: `Light`/`Dark`/`System`/`Monochromatic`/`Frosted Texture`
- **Cache Mode**: echoi reimagines interaction without the traditional concept of browser tabs. In this mode, links accessed via the sidebar are cached for quick swapping (accessible via `Menu -> Settings -> Cache Mode`).
- **Cookie Data Isolation**: Supports the use of multiple accounts on the same website, catering to diverse user requirements.
- **Discover More**: There are numerous details waiting for your discovery...

## ⬇️ Download

[🕒 History versions...](https://github.com/ReZonArc/echoi/releases)

- **macOS**
  - [⬇️ x64](https://github.com/ReZonArc/echoi/releases/download/v0.4.0/echoi_macos_0.4.0.dmg)
  - [⬇️ arm64](https://github.com/ReZonArc/echoi/releases/download/v0.4.0/echoi_macos_0.4.0-arm64.dmg)
- **Windows**
  - [⬇️ x64](https://github.com/ReZonArc/echoi/releases/download/v0.4.0/echoi-win32-x64-0.4.0-setup.exe)
- **Linux**
  - [⬇️ AppImage](https://github.com/ReZonArc/echoi/releases/download/v0.4.0/echoi_linux_0.4.0.AppImage)
  - [⬇️ amd64.deb](https://github.com/ReZonArc/echoi/releases/download/v0.4.0/echoi_linux_amd64_0.4.0.deb)

|Preview|Preview|
|---|---|
|![theme-dark-1](./website/static/readme/noi-theme-dark-1.png)|![theme-dark-2](./website/static/readme/noi-theme-dark-2.png)|
|![theme-light-1](./website/static/readme/noi-theme-light-1.png)|![theme-light-2](./website/static/readme/noi-theme-light-2.png)|
|![noi-settings](./website/static/readme/noi-settings.png)|![noi-prompts](./website/static/readme/noi-prompts.png)|

## ⚙️ echoi Configs

[📁 configs](./configs)

### Mode

To set up a custom sync link, follow the steps below:

- **Step 1**: Open the settings (on macOS: `cmd`+`,`, on Windows: `ctrl`+`,`)
- **Step 2**: Edit the URL in `Mode Sync`
- **Step 3** or **Step 4**: Click the `sync` button to start synchronizing data

> [!NOTE]
> The `custom url` will not be overwritten. If you wish to use your own URL as a data source, please refer to the data format in `noi.mode.json`.

![Mode Sync](./website/static/configs/noi-mode-sync.png)

#### Sync URL

- [AI](configs/noi.mode.json): Popular AI websites and communities (e.g., ChatGPT, Gemini, Claude, Poe, etc.).

  ```bash
  https://raw.githubusercontent.com/ReZonArc/echoi/main/configs/noi.mode.json
  ```

- [AI（内陆版）](configs/noi.mode.cn.json): 主流 AI 及国内 AI（如：通义千问、扣子、豆包、智谱清言、讯飞星火、文心一言等）。

  ```bash
  https://raw.githubusercontent.com/ReZonArc/echoi/main/configs/noi.mode.cn.json
  ```

#### noi.mode.json

Here is a detailed description of some fields:

- `name`: Name (optional, has no significance)
- `version`: Version change
- `sync`: URL information (optional, has no significance)
- `modes[]`:
  - `id`: A unique identifier (use a random string; do not use formats like `noi:xxx` or `noi@xxx` as these are reserved for internal use)
  - `parent`: The parent folder this item belongs to (supports nesting)
  - `text`: Name
  - `url`: Link
  - `dir`: Whether it is a folder, default is `false`

### Proxy

Learn more: [electronjs/docs](https://www.electronjs.org/docs/latest/api/session#sessetproxyconfig)

- `proxyRules`: Rules indicating which proxies to use.
- `proxyBypassRules`: Rules indicating which URLs should bypass the proxy settings.

## 🧩 echoi Extensions

[📁 extensions](./extensions)

Note that echoi does not support the full range of Chrome extensions APIs. See Supported Extensions APIs for more details on what is supported.

Learn more: [electronjs/doc](https://www.electronjs.org/docs/latest/api/extensions)

<!-- EXTENSIONS_START -->
| Name | Version | Description |
| --- | --- | --- |
| [@noi/ask](https://github.com/ReZonArc/echoi/tree/main/extensions/noi-ask) | 0.2.2 | The best assistant for batch asking and quick typing of prompts. |
| [@noi/ask-custom](https://github.com/ReZonArc/echoi/tree/main/extensions/noi-ask-custom) | 0.1.0 | The best assistant for batch asking and quick typing of prompts. |
| [@noi/reset](https://github.com/ReZonArc/echoi/tree/main/extensions/noi-reset) | 0.1.3 | Reset certain website styles to enhance compatibility with echoi. |
<!-- EXTENSIONS_END -->

[![Star History Chart](https://api.star-history.com/svg?repos=ReZonArc/echoi&type=Timeline)](https://star-history.com/#ReZonArc/echoi&Timeline)

# 🌐 echoi Languages

[📁 locales](./locales)

- `en`: English
- `fa`: فارسی
- `zh`: 简体中文
- `zh_Hant`: 繁體中文
- `ja`: 日本語
- `ko`: 한국어
- `fr`: Français
- `es`: Español
- `pt`: Português
- `ru`: Русский
- `de`: Deutsch
- `it`: Italiano
- `tr`: Türkçe
- `hu`: Magyar

## ⚠️ FAQ

### macOS

If you encounter the error message "echoi" is damaged and can't be opened. You should move it to the Trash. while installing software on macOS, it may be due to security settings restrictions in macOS.

![mac-install-error](./website/static/readme/mac-install-error.jpg)

To solve this problem, please choose Apple menu  > System Preferences, then click Security & Privacy and choose General tab:

![](./website/static/readme/fix-mac-install-error.png)

or try the following command in Terminal:

```bash
xattr -cr /Applications/echoi.app
```
