# Nova APK Builder 🚀

**Build Android APK files from native Android Gradle projects — directly on Windows.**

Nova APK Builder is a simple desktop application that helps you build Android debug APKs from ZIP files containing Android Gradle projects, without manually setting up the Android development environment.

## ✨ Features

- 🖥️ Simple desktop interface with Persian RTL support
- 📦 Import Android projects as ZIP files
- ⚙️ Automatically downloads and configures required build tools
- ☕ Automatic JDK 17 setup
- 🛠️ Android SDK and Gradle support
- 📋 Live build logs and error messages
- 📂 Automatically saves the generated APK to your Desktop
- 🌙 Dark-themed interface
- 💻 Portable Windows executable — no installer required

## 🧰 Requirements

- Windows 10 or Windows 11 (64-bit)
- Internet connection for the initial setup and downloading dependencies
- A ZIP file containing a native Android Gradle project

The first build may download approximately 1–2 GB of development tools and dependencies.

## 🚀 How to Use

1. Download and run **Nova APK Builder**.
2. Select a ZIP file containing your Android Gradle project.
3. Wait while the required tools are downloaded and configured.
4. Follow the live build logs.
5. After a successful build, find your APK in `Desktop/Nova APK Output`.

## ⚠️ Limitations

- Currently supports native Android Gradle projects only.
- Does not currently support Flutter, React Native, Unity, Capacitor, or Cordova projects.
- Currently generates **debug APKs only**.
- Release signing and Android App Bundle (AAB) generation are not yet supported.
- Projects requiring incompatible Java or Gradle versions may fail to build.
- Build errors in the original Android project must be fixed separately.

## 🔒 Security

Only build projects you trust. Android Gradle build scripts can execute code on your computer.

Download the application only from the official GitHub repository and Releases page. The executable may trigger Windows SmartScreen or antivirus warnings because it is not digitally signed.

## 🗺️ Roadmap

- [ ] English interface option
- [ ] Release APK signing
- [ ] Android App Bundle (AAB) support
- [ ] Selectable JDK versions
- [ ] Proxy and mirror configuration
- [ ] Improved project compatibility

## 👨‍💻 Author

**Nova**

- GitHub: https://github.com/Nova2585nd
- X: https://x.com/Nova_2585_nd
- Telegram: https://t.me/Nova_2585

## 📌 Project Status

Early release — **v1.0.0**

Features and compatibility may change as development continues.

## ⚖️ Disclaimer

Nova APK Builder is an independent project and is not affiliated with Google, Android, or Gradle. Android is a trademark of Google LLC.
