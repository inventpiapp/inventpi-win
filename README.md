
<div align="center">
    <!-- Hero Section with Gradient Background Effect -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://avatars.githubusercontent.com/u/257929584">
  <img src="https://avatars.githubusercontent.com/u/257929584" width="140" alt="InventPi Logo">
</picture>

# InventPi

<h3>
  <img src="https://avatars.githubusercontent.com/u/257929584?s=48&v=4" width="25" height="25" />
  <i>Invention Driven by Passion and Intelligence</i>
  <img src="https://avatars.githubusercontent.com/u/257929584?s=48&v=4" width="25" height="25" />
</h3>

![Release](https://img.shields.io/badge/release-v2.0.0-blue)
![Platform](https://img.shields.io/badge/platform-Windows-success)
![Future](https://img.shields.io/badge/Linux%20%7C%20macOS-Planned-lightgrey)
![Status](https://img.shields.io/badge/status-Stable-success)

</div>

---

##  🪟 InventPi Windows App
InventPi is a comprehensive inventory and billing solution specifically designed to support growing businesses. Our application helps you manage your inventory, process sales, generate bills, and track your business performance with ease.

With an intuitive interface and powerful features, InventPi streamlines your business operations, allowing you to focus on what matters most - growing your business.

# Installation Guide 

This guide explains how to download, verify, and run the InventPi app on Windows using the official release files:

- `win_InventPi_2.0.0_installer.exe`
- `win_InventPi_2.0.0_portable.exe`

There is also an **optional** file stored in the **InventPi Git repository** (not in the release Assets section):

- `InventPiCert.cer` (code-signing certificate, only needed if you continue to see signing / SmartScreen warnings)


---

## 1. Downloading InventPi ⬇️

1. Open the official InventPi release page.
2. In the **Assets** section for version `2.0.0`, download the following **EXE files**:
   - **Recommended for most users:** `win_InventPi_2.0.0_installer.exe`
   - **Advanced / portable use:** `win_InventPi_2.0.0_portable.exe`
3. Save the files to a folder you can easily find, for example `Downloads`.

> The optional certificate file `InventPiCert.cer` is **not** in the Assets list. It is provided inside the main InventPi Git code repository (for example in a `cert` or `security` folder). Only download it from the official repository location if you need it.

---

## 2. Installer vs Portable – Which one should I use? 🤔

### 2.1 `win_InventPi_2.0.0_installer.exe` (Recommended) ✅

Use this if you:

- Want a **standard Windows installation**.
- Prefer **Start Menu and Desktop shortcuts**.
- Want InventPi to be **easier to open** like any other app.

What it does:

- Installs InventPi on your system (for example under `C:\Program Files\InventPi` or a similar folder).
- Creates shortcuts in the **Start Menu** and optionally on the **Desktop**.
- Registers InventPi properly so you can uninstall it from **“Apps & Features”** in Windows settings.

### 2.2 `win_InventPi_2.0.0_portable.exe` (Portable version) 📁

Use this if you:

- Prefer **no installation** and want to keep everything in a single folder.
- Want to run InventPi from a **USB drive** or a non‑system location.
- Do not need Start Menu or Desktop shortcuts.

What it does:

- You simply place `win_InventPi_2.0.0_portable.exe` in any folder you like.
- When you run it, InventPi starts without modifying system‑wide settings.
- All application data is still stored under your user profile (for example in `Documents\InventPi`), but the main program files stay in that folder.

If you are not sure which one to choose, use the **installer version**.

---

## 3. Optional: Installing the Code‑Signing Certificate (`InventPiCert.cer`) 🔐

This section is **optional**. In many cases you can install and run InventPi without doing this.

However, if you continue to see signing or SmartScreen warnings even after confirming the app is from the official InventPi release page, installing the `InventPiCert.cer` certificate can help Windows better recognize InventPi as a trusted application.

### 3.1 Download the certificate from the Git repository (only if needed)

1. Open the official InventPi Git code repository in your browser.
2. Locate the `InventPiCert.cer` file (for example in a `cert` or `security` folder).
3. Download `InventPiCert.cer` **only if you are still seeing trust / signing warnings**.
4. Save it in the same folder as the EXE files (for example `Downloads`).

### 3.2 Install the certificate (Current User)

1. Locate the file `InventPiCert.cer` in File Explorer.
2. **Right‑click** on the file and select **Install Certificate…**.
3. In the Certificate Import Wizard:
   - Choose **Current User** (recommended), then click **Next**.
4. Select **Place all certificates in the following store**, then click **Browse…**.
5. Choose **Trusted Publishers** (or **Trusted Root Certification Authorities** if instructed), then click **OK**.
6. Click **Next**, then **Finish**.
7. If Windows asks you to confirm, click **Yes** or **Allow**.

After this, Windows will treat InventPi builds signed with this certificate as more trusted, which may reduce security prompts and warnings.

> Note: You may need administrator rights if installing to system‑wide certificate stores. Using **Current User → Trusted Publishers** usually does not require full admin access.

---

## 4. Installing InventPi using the Installer EXE (Recommended) 🛠️

Follow these steps for `win_InventPi_2.0.0_installer.exe`:

1. (Optional) If you often see signing / SmartScreen warnings, consider installing `InventPiCert.cer` first (see Section 3).
2. In File Explorer, go to the folder where you saved `win_InventPi_2.0.0_installer.exe`.
3. **Double‑click** `win_InventPi_2.0.0_installer.exe`.
4. If Windows shows a security prompt (SmartScreen or "Do you want to allow this app to make changes?"), review the publisher information and then click **Yes** / **Run anyway** if it matches InventPi.
5. Follow the on‑screen installer steps:
   - Choose the installation folder (you can usually accept the default).
   - Keep **“Create Desktop Shortcut”** checked if you want a desktop icon 📁.
   - Click **Install** and wait for the process to complete.
6. When installation is finished, click **Finish**.

### 4.1 Starting InventPi after installation 🚀

You can start InventPi in several ways:

- From the **Desktop shortcut** named **InventPi** (if you created one).
- From the **Start Menu**: open Start, search for **InventPi**, and click it.

The app will start, open its main window, and be ready to use.

---

## 5. Using the Portable EXE 🚀

If you chose `win_InventPi_2.0.0_portable.exe`:

1. Create a folder where you want to keep InventPi portable (for example `C:\Tools\InventPi` or on a USB drive).
2. Move or copy `win_InventPi_2.0.0_portable.exe` into that folder.
3. (Optional) If you often see signing / SmartScreen warnings, you may install `InventPiCert.cer` (Section 3) to reduce security prompts.
4. **Double‑click** `win_InventPi_2.0.0_portable.exe` to run it.

Notes:

- The app does not add Uninstall entries or Start Menu shortcuts automatically.
- To create an easy shortcut, you can **right‑click** the EXE → **Send to → Desktop (create shortcut)**.
- To "uninstall" the portable version, simply close the app and delete the EXE file and its folder (your data in `Documents\InventPi` may remain unless you remove it manually).

---

## 6. Troubleshooting ⚠️

- **Windows SmartScreen warning** ⚠️
  - Click **More info** → verify the publisher → click **Run anyway** (only if you downloaded the file from the official InventPi release page).
  - If warnings continue to appear frequently, you can **optionally** install `InventPiCert.cer` as described above to help Windows recognize InventPi.

- **Installer cannot run or is blocked**
  - Ensure you are logged into Windows with a user that has permission to install software.
  - Temporarily pause overly strict antivirus software if it incorrectly flags the installer, then run the installer again.

- **Application does not start after install**
  - Try running InventPi from the Start Menu instead of a pinned shortcut.
  - Reboot Windows and start InventPi again.

If problems continue, please contact InventPi support and mention which file you used (`installer` or `portable`) and your version of Windows.

---

## 7. Summary 📌

- Use **`win_InventPi_2.0.0_installer.exe`** for a normal, fully installed Windows app with shortcuts and an uninstaller.
- Use **`win_InventPi_2.0.0_portable.exe`** if you prefer a single‑file, no‑install version (for example on a USB stick).
- Optionally install **`InventPiCert.cer`** if you continue to see signing / SmartScreen warnings and want Windows to better recognize InventPi executables as trusted.

This document is specifically for the **Windows** release of InventPi version **2.0.0**.
