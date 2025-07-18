<h1 align="center">🚀 C++ Redistributable Installer</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/Built%20With-Batch-ff69b4?style=flat-square" alt="Batch Script" />
  <img src="https://img.shields.io/badge/Installs-All%20Major%20C++%20Runtimes-brightgreen?style=flat-square" alt="Coverage" />
</p>

---

### 📦 What is this?

A simple batch script that **automatically downloads and installs** all major Microsoft C++ Redistributable packages from **2005 to 2022** — both x86 and x64.

No more hunting for individual installers. Just run it and you're good to go. ✅

---

### 🧰 What's Included?

This script installs the following Visual C++ Redistributables:

- ✔️ **2005**
- ✔️ **2008**
- ✔️ **2010**
- ✔️ **2012**
- ✔️ **2013**
- ✔️ **2015–2022 (Universal Runtime)**

---

### 🛠️ How to Use

1. **Download** or clone this repo.
2. **Right-click** the `install_cpp.bat` file and select `Run as administrator`.
3. Sit back and let the script do its thing! 💻☕

> ⚠️ Note: An internet connection is required to download the redistributables.

---

### 🔍 How It Works

- Uses `curl` to download the official Microsoft redistributables.
- Stores them in your `%TEMP%` directory.
- Silently installs each one using flags like `/q`, `/qb`, and `/passive`.

---

### 💡 Why You Might Need This

Many games, tools, and development environments require specific C++ runtimes. This script ensures **you're fully covered** in just a few minutes.

---

### 🧪 Tested On

- Windows 10 ✅  
- Windows 11 ✅  
- Should also work on Windows Server editions.

---

### 🤝 Credits

Created by **[RonnieColeman9](https://github.com/RonnieColeman9)**  
Feel free to fork, modify, and contribute!
