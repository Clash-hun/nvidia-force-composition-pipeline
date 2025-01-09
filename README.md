# 🚀 NVIDIA Force Composition Pipeline Script 🖥️✨

## 📌 What is the NVIDIA Force Composition Pipeline?
The NVIDIA Force Composition Pipeline is a powerful tool that helps to eliminate screen tearing by enforcing a composition pipeline in the NVIDIA settings. This is particularly useful for systems using NVIDIA GPUs where screen tearing can be an issue during video playback, gaming, or general desktop use.

![NVIDIA Settings](https://kephost.net/p/MTY1Nzg0NQ.png)

---

## 🛠️ Step-by-Step Guide
Follow these simple steps to set up the NVIDIA Force Composition Pipeline script to run automatically at startup:

1️⃣ **Create the autostart directory:**
   ```bash
   mkdir -p ~/.config/autostart
   ```

2️⃣ **Create the startup script file:**
   ```bash
   nano ~/.config/autostart/nvidia-force-composition-pipeline.desktop
   ```

3️⃣ **Add the following content to the file:**
   ```plaintext
   [Desktop Entry]
   Type=Application
   Name=NVIDIA Force Composition Pipeline
   Exec=nvidia-settings --assign CurrentMetaMode="nvidia-auto-select +0+0 { ForceCompositionPipeline = On }"
   Hidden=false
   X-GNOME-Autostart-enabled=true
   ```

   Save the file with **Ctrl+O**, confirm, and then exit with **Ctrl+X**.

4️⃣ **Make the script executable:**
   ```bash
   chmod +x ~/.config/autostart/nvidia-force-composition-pipeline.desktop
   ```

5️⃣ **Restart your system:**
   Once your system restarts, the NVIDIA Force Composition Pipeline will be enabled automatically. 🎉

---

## 💡 Notes
- Make sure you have the NVIDIA drivers properly installed on your system.
- This script is designed for Linux environments with NVIDIA GPUs.

## 🌟 Why Use This Script?
This script ensures that the Force Composition Pipeline is enabled at every startup, saving you the hassle of manually configuring it each time. 🖥️✨

Enjoy tear-free visuals with your NVIDIA GPU! 🟩

## ☕ Support
If you found this helpful, consider supporting me with a coffee:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-%23FFDD00.svg?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://paypal.me/clash2un?country.x=HU&locale.x=hu_HU)


