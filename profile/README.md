<div align="center">

![Evolution X Banner](https://github.com/Evolution-X/.github/raw/refs/heads/main/profile/Banner.svg)

**Pixel features. AOSP foundation. Your device, evolved.**

[Website](https://evolution-x.org) · [Devices](https://evolution-x.org/devices) · [Downloads](https://cdn.evolution-x.org) · [Features](https://evolution-x.org/features) · [Wiki](https://wiki.evolution-x.org) · [Blog](https://evolution-x.org/blog)

<a href="https://discord.gg/evolution-x-670512508871639041"><img src="https://img.shields.io/badge/Discord-Join-5865F2?style=flat-square&logo=discord&logoColor=white"/></a>
<a href="https://t.me/EvolutionXOfficial"><img src="https://img.shields.io/badge/Telegram-Channel-01A9E0?style=flat-square&logo=telegram&logoColor=white"/></a>
<a href="https://t.me/EvolutionX"><img src="https://img.shields.io/badge/Telegram-Chat-01A9E0?style=flat-square&logo=telegram&logoColor=white"/></a>
<a href="https://x.com/EvolutionXROM"><img src="https://img.shields.io/badge/X-Follow-000000?style=flat-square&logo=x&logoColor=white"/></a>
<a href="https://crowdin.com/project/Evolution_X"><img src="https://img.shields.io/badge/Crowdin-Translate-2E3340?style=flat-square&logo=crowdin&logoColor=white"/></a>
<br/>
<a href="https://github.com/Evolution-X/manifest/stargazers"><img src="https://img.shields.io/github/stars/Evolution-X/manifest?style=flat-square&color=6C63FF&label=Stars"/></a>
<a href="https://github.com/Evolution-X/frameworks_base/commits/cnb"><img src="https://img.shields.io/github/last-commit/Evolution-X/frameworks_base/cnb?style=flat-square&color=00D4AA&label=Last+Commit"/></a>

</div>

> [!NOTE]
> **Current focus: Android 17 (`cnb`).** New features, fixes, and device bring-up land there first. Android 16 (`bka`) and Android 15 (`vic`) stay actively maintained, with a stability-focused cadence for most supported devices.

---

## 📲 Get Evolution X

| | Step | Where |
|---|------|-------|
| **1** | Check that your device is supported | [evolution-x.org/devices](https://evolution-x.org/devices) |
| **2** | Download the latest build. Android 17 (`cnb`) builds get the newest features, so look there first | [cdn.evolution-x.org](https://cdn.evolution-x.org) |
| **3** | Follow the install guide for your device | [wiki.evolution-x.org](https://wiki.evolution-x.org) |

<details>
<summary><b>Quick overview of the flashing process</b></summary>

<br>

1. Boot into a custom recovery (for example TWRP or OrangeFox)
2. Flash the ROM zip, and flash GApps if your build doesn't include them
3. Wipe cache/dalvik and reboot

Steps can differ per device, so always check the [Wiki](https://wiki.evolution-x.org) for yours.

</details>

> [!WARNING]
> Back up your data before flashing. Installing a custom ROM can void your warranty.

---

## ✨ Why Evolution X

Evolution X blends the best of Pixel with deep customization, on top of a clean LineageOS base.

| | |
|---|---|
| 🌟 **Pixel exclusives** | Wallpapers, clock styles, boot animations, sound effects, unlimited Google Photos backup and more, straight from Pixel |
| 🛠️ **Deep customization** | Freeform windows, Sidebar, App Lock, per-app volume, icon packs, font switching and hundreds of UI tweaks, all in [**Evolver**](https://github.com/Evolution-X/packages_apps_Evolver), our in-house settings app |
| 🔁 **Always up to date** | Monthly Android security patches, fast rebases and consistent stable releases |
| 🌍 **Community translated** | Localized into dozens of languages by volunteers on Crowdin |
| 🧠 **Active community** | Thousands of users and maintainers on Discord and Telegram, so help is always close |
| 🔓 **Fully open source** | Every line of code is public. Audit it, fork it, learn from it |

---

## 📱 Supported Android Versions

<div align="center">

| Branch | Status | Devices | Manifest |
|--------|--------|:-------:|----------|
| 🔵 **Android 17** | ![Primary Focus](https://img.shields.io/badge/Primary%20Focus-FF6C37?style=flat-square) | 4 (early bring-up) | [cnb](https://github.com/Evolution-X/manifest/commits/cnb) |
| 🟣 **Android 16 QPR2** | ![Maintained](https://img.shields.io/badge/Maintained-6C63FF?style=flat-square) | 40 | [bka](https://github.com/Evolution-X/manifest/commits/bka) |
| 🟢 **Android 15** | ![Maintained](https://img.shields.io/badge/Maintained-00D4AA?style=flat-square) | 3 | [vic](https://github.com/Evolution-X/manifest/commits/vic) |
| ⚪ **Android 14** | ![Legacy](https://img.shields.io/badge/Legacy-888888?style=flat-square) | 0 (no longer maintained) | [udc](https://github.com/Evolution-X/manifest/commits/udc) |

<sub>Device counts come from entries flagged `currently_maintained: true` in the [OTA directory](https://github.com/Evolution-X/OTA) with a build in the last 2 months.</sub>

</div>

---

## 🤝 Get Involved

There are a few easy ways to help, whatever your skill set.

<details>
<summary><b>🔧 Become a device maintainer</b></summary>

<br>

Want to maintain Evolution X for your device? We especially need help bringing devices up on the **Android 17 (`cnb`)** branch. Reach out on [Discord](https://discord.gg/evolution-x-670512508871639041) and contact **Onelots** or **Manidweep**.

</details>

<details>
<summary><b>⚙️ Contribute to Evolver, our settings app</b></summary>

<br>

Most user-facing customization lives in **[Evolver](https://github.com/Evolution-X/packages_apps_Evolver)**. If you're comfortable with Java/Kotlin and Android UI work, it's one of the most approachable places to start, from small preference-screen cleanups to new Compose-based features.

1. Fork [packages_apps_Evolver](https://github.com/Evolution-X/packages_apps_Evolver) and check the [`cnb`](https://github.com/Evolution-X/packages_apps_Evolver/commits/cnb) branch for the latest work
2. Browse open issues, or ask on [Discord](https://discord.gg/evolution-x-670512508871639041) for good first tasks
3. Submit a pull request. Gerrit-style commit messages are appreciated

</details>

<details>
<summary><b>🌍 Help translate</b></summary>

<br>

Evolution X is localized by volunteers on **[Crowdin](https://crowdin.com/project/Evolution_X)**. No technical knowledge needed.

1. Open [crowdin.com/project/Evolution_X](https://crowdin.com/project/Evolution_X) and sign in (it's free)
2. Pick your language
3. Start translating strings. Translations are reviewed and merged into the ROM regularly

Even a few translated strings help users in your region.

</details>

---

## 👥 Contributors

Evolution X is built by contributors across the whole org: manifest, frameworks, device trees and Evolver.

<div align="center">

**Core manifest & frameworks**

[![Contributors](https://contrib.rocks/image?repo=Evolution-X/manifest&max=24&columns=12)](https://github.com/Evolution-X/manifest/graphs/contributors)

**Evolver (settings app)**

[![Contributors](https://contrib.rocks/image?repo=Evolution-X/packages_apps_Evolver&max=24&columns=12)](https://github.com/Evolution-X/packages_apps_Evolver/graphs/contributors)

</div>

---

## 🔐 Security & Transparency

Evolution X is **fully open source**, from system components to build scripts. When choosing any custom ROM, we recommend:

- ✅ Confirming the source code is publicly available
- ✅ Reviewing recent commit history and development activity
- ✅ Checking maintainer reputation and community trust

---

## 🔗 Resources

| | |
|---|---|
| 📦 **Manifest** | [Evolution-X/manifest](https://github.com/Evolution-X/manifest) · [Android 17 (`cnb`)](https://github.com/Evolution-X/manifest/tree/cnb) |
| ⚙️ **Evolver** | [packages_apps_Evolver](https://github.com/Evolution-X/packages_apps_Evolver) |
| 📁 **Device trees** | [Evolution-X-Devices](https://github.com/Evolution-X-Devices) |
| 🌍 **Translations** | [Crowdin](https://crowdin.com/project/Evolution_X) |
| 🐦 **X / Twitter** | [@EvolutionXROM](https://x.com/EvolutionXROM) |

---

<div align="center">

### 💖 Support the project

[![Joey](https://img.shields.io/badge/Joey-Lead%20Developer-00D4AA?style=for-the-badge&logo=linktree&logoColor=white)](https://linktr.ee/joeyhuab)

**Now focused on Android 17. Let's keep evolving Android together 🚀**

</div>
