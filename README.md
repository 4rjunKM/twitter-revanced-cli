# 🐦 X (Twitter) ReVanced — CLI Patch Setup

![Build](https://img.shields.io/badge/build-ReVanced%20CLI-orange)
![Platform](https://img.shields.io/badge/platform-Android-green)
![Architecture](https://img.shields.io/badge/arch-universal-blue)
![Java](https://img.shields.io/badge/java-11%2B-red)
![License](https://img.shields.io/badge/license-GPL--3.0-lightgrey)

Minimal and clean **ReVanced CLI** setup for patching the official X (Twitter) Android application locally.

👉 Repository: https://github.com/4rjunKM/twitter-revanced-cli

This project provides configuration files and scripts to apply ReVanced patches using your own base APK.

---

## ⚠️ Disclaimer

* This repository **does not distribute** proprietary APK files.
* Users must supply their own legally obtained base APK.
* Educational and development use only.
* Compatibility may change when X releases updates.

---

## ✨ Included Patches (Current Build)

* 🚫 **Hide ads** — removes promoted tweets and sponsored content
* 👤 **Hide recommended users** — cleans follow suggestions
* 🎨 **Dynamic color** — enables Material You style theming
* 🔗 **Sanitize sharing links** — cleans tracking parameters from shared URLs
* 🎥 **Unlock downloads** — enables media download support

Patch availability depends on upstream ReVanced patches.

---

## 📋 Requirements

* Java 11 or newer
* ReVanced CLI
* ReVanced Patches
* Official X APK (user supplied)

---

## 🚀 Usage

### Clone Repository

```
git clone https://github.com/4rjunKM/twitter-revanced-cli
cd twitter-revanced-cli
```

### Prepare Files

Place:

```
revanced-cli.jar
revanced-patches.jar
```

Put your base APK inside:

```
/input/twitter.apk
```

### Run Build

Windows:

```
build.bat
```

Linux / macOS:

```
bash build.sh
```

---

## 📦 Output

The patched APK will be generated inside the `output` folder after the build completes.

---

## 🔧 Customization

Edit `patches.json` to enable or disable supported patches.

---

## 🤝 Contributing

Pull requests are welcome.
Fork → Commit → Open PR.

---

## 📜 License

GPL-3.0 License

---

## ⭐ Notes

This repository is a CLI workflow wrapper.
It simplifies patching but does not create or maintain patches itself and relies on upstream ReVanced tools.
