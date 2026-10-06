<div align="center">

<!-- Replace with your logo: put it in Screenshots/logo.png -->
<img src="Screenshots/logo.png" alt="Hyro Music" width="120" height="120" />

# Hyro Music

**A beautiful, fast and ad-free music player for Android.**
Built with Kotlin and Jetpack Compose. Designed to feel premium.

[![Latest Release](https://img.shields.io/github/v/release/BL4ZE-LEG1T/Hyro?style=for-the-badge&color=7C4DFF&label=Latest)](https://github.com/BL4ZE-LEG1T/Hyro/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/BL4ZE-LEG1T/Hyro/total?style=for-the-badge&color=00C853&label=Downloads)](https://github.com/BL4ZE-LEG1T/Hyro/releases)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge)](LICENSE)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-Jetpack_Compose-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

[**⬇️ Download APK**](https://github.com/BL4ZE-LEG1T/Hyro/releases/latest) &nbsp;•&nbsp;
[Website](https://your-website-here.com) &nbsp;•&nbsp;
[Report a Bug](https://github.com/BL4ZE-LEG1T/Hyro/issues) &nbsp;•&nbsp;
[Request a Feature](https://github.com/BL4ZE-LEG1T/Hyro/issues)

</div>

---

## ✨ Why Hyro Music?

Hyro Music is built around one idea: your music should look as good as it sounds. Clean visuals, smooth animations, synced lyrics and a polished playlist experience, all in one lightweight app.

## 📸 Screenshots

<div align="center">

| Home | Player | Playlist | Lyrics |
|:---:|:---:|:---:|:---:|
| <img src="Screenshots/home.png" width="200" /> | <img src="Screenshots/player.png" width="200" /> | <img src="Screenshots/playlist.png" width="200" /> | <img src="Screenshots/lyrics.png" width="200" /> |

</div>

> Add your screenshots to the `Screenshots/` folder using the names above.

## 🎯 Features

- 🎨 **Premium Material You design** built entirely with Jetpack Compose
- 🎵 **Smooth playback** with a full-featured player and queue
- 📝 **Synced lyrics** from multiple providers
- 📂 **Playlists** with a refined, polished screen
- 🔄 **In-app updates** and a built-in changelog
- 💬 **Discord Rich Presence** support
- 🤝 **Listen Together** sessions
- 🚫 **No ads, no tracking**

## 📥 Download & Install

1. Go to the [**Releases page**](https://github.com/BL4ZE-LEG1T/Hyro/releases/latest).
2. Download the latest `.apk` file.
3. Open it on your Android phone and allow **Install from unknown sources** if asked.
4. Enjoy.

**Requirements:** Android 8.0 (API 26) or higher. *(Update this if your minimum version is different.)*

## 🛠️ Build From Source

```bash
# 1. Clone the repo
git clone https://github.com/BL4ZE-LEG1T/Hyro.git
cd Hyro

# 2. Copy the template config files and fill in your own values
cp gradle.properties.template gradle.properties
cp local.properties.template local.properties

# 3. Build a release APK
./gradlew :app:assembleArm64FossRelease
```

On Windows, use `.\gradlew.bat` instead of `./gradlew`.
The APK will be in `app/build/outputs/apk/arm64Foss/release/`.

See [SETUP.md](SETUP.md) for detailed setup instructions.

## 🧰 Tech Stack

| Area | Technology |
|---|---|
| Language | Kotlin |
| UI | Jetpack Compose, Material 3 |
| Database | Room |
| Build | Gradle (Kotlin DSL) |
| Platform | Android |

## 🤝 Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) and our [Code of Conduct](CODE_OF_CONDUCT.md) first, then open an issue or pull request.

## 🔒 Privacy & Security

- Privacy policy: [PRIVACY_POLICY.md](PRIVACY_POLICY.md)
- Found a vulnerability? See [SECURITY.md](SECURITY.md).

## 🙏 Credits & Acknowledgements

Hyro Music is built on top of open-source work, and full credit goes to the original authors:

- **[Echo Music](https://github.com/iad1tya/Echo-Music)** by iad1tya, the foundation this app grew from
- The open-source projects whose code and APIs are used in this repo, including InnerTube, LrcLib, KuGou, SimpMusic, YouLyPlus, BetterLyrics, Paxsenix Lyrics and others

Thank you to every developer who makes their work open for others to learn from and build on.

## 📜 License

Hyro Music is released under the **[GNU General Public License v3.0](LICENSE)**.

You are free to use, study, modify and share this software under the terms of that license. Any distributed modified version must also be released under GPL-3.0 with its source code available.

---

<div align="center">

Made with ❤️ by **[BL4ZE-LEG1T](https://github.com/BL4ZE-LEG1T)**

If you like Hyro Music, consider giving the repo a ⭐

</div>
