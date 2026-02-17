# 🐦 X (Twitter) ReVanced — CLI Patch Setup

![Build](https://img.shields.io/badge/build-ReVanced%20CLI-orange)
![Platform](https://img.shields.io/badge/platform-Android-green)
![Architecture](https://img.shields.io/badge/arch-arm64--v8a-blue)
![Java](https://img.shields.io/badge/java-11%2B-red)
![License](https://img.shields.io/badge/license-GPL--3.0-lightgrey)

A minimal and clean **ReVanced CLI** setup for patching the official X (Twitter) Android application locally.

👉 Repository: https://github.com/4rjunKM/twitter-revanced-cli

This project provides configuration files and scripts to help users apply ReVanced patches using their own base APK.

---

## ⚠️ Disclaimer

* This repository **does not provide** or distribute proprietary APK files.
* Users must supply their own legally obtained base APK.
* This project is for educational and development purposes only.
* Compatibility may break when the X app updates.

---

## ✨ Features

* Simple CLI-based patch workflow
* ARM64 build focus
* Lightweight configuration
* Windows and Linux build scripts
* Easy customization

---

## 📥 Required Downloads

Download the required tools from official sources:

### ReVanced CLI

https://github.com/revanced/revanced-cli/releases

### ReVanced Patches

https://github.com/revanced/revanced-patches/releases

### ReVanced Integrations (if required)

https://github.com/revanced/revanced-integrations/releases

---

## 📋 Requirements

* Java 11 or newer installed
* Official X (Twitter) APK (user supplied)
* ReVanced CLI JAR file
* ReVanced Patches JAR file

Recommended tools:

* apktool
* uber-apk-signer

---

## 🚀 Usage

### 1️⃣ Clone Repository

```
git clone https://github.com/4rjunKM/twitter-revanced-cli
cd twitter-revanced-cli
```

### 2️⃣ Prepare Files

Place the following files in the root folder:

```
revanced-cli.jar
revanced-patches.jar
```

Add your base APK inside:

```
/input/twitter.apk
```

---

### 3️⃣ Run Build Script

Windows:

```
build.bat
```

Linux / macOS:

```
bash build.sh
```

---

### 4️⃣ Output

The patched APK will be generated inside the output folder after the process finishes.

---

## 🔧 Customization

You can edit the `patches.json` file to enable or disable specific patches depending on availability.

Actual supported patches depend on the upstream ReVanced patches project.

---

## 🤝 Contributing

Pull requests and improvements are welcome.

If you enhance scripts or configuration:

1. Fork the repository
2. Create a new branch
3. Submit a pull request

---

## 📜 License

GPL-3.0 License

---

## ⭐ Notes

This repository is a CLI wrapper workflow designed to simplify patching.
It does not create or maintain patches itself and relies on upstream ReVanced tools.
