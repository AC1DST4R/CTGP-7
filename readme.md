# CTGP-7 Offline 3DSX Installation Package

This repository contains the manual offline installation files and instructions for **CTGP-7** (the definitive custom track modpack for *Mario Kart 7*) using the 3DS Homebrew Launcher `.3dsx` format. 

This standalone method allows you to install the entire ~1GB modpack entirely on your console using files pre-loaded onto your SD card, making it ideal if your 3DS has a slow or unreliable internet connection.

##  Prerequisites
Before starting, ensure your system meets the following requirements:
*   A Nintendo 3DS / 2DS console with **Custom Firmware (Boot9Strap + Luma3DS)**.
*   The **Homebrew Launcher** installed and accessible.
*   An installed copy of **Mario Kart 7** (Physical or Digital) updated to the latest **v1.2**.
*   An SD card with at least **3GB of free space** (the mod requires ~1GB, but extra buffer space is needed on-console during the extraction process).
*   **FBI** (or any CIA installer) to install the home menu forwarder icon.

---

##  Installation Steps

### 1. File Placement
1. Power off your 3DS and insert the SD card into your computer.
2. Copy the `CTGP-7` folder from this package directly into the **root** of your SD card.
3. Copy the `CTGP-7_Installer.3dsx` file into the `3ds/` folder on your SD card. 
   *(Your file path should look like: `SD:/3ds/CTGP-7_Installer.3dsx`)*.
4. Safely eject the SD card and reinsert it into your 3DS.

### 2. On-Console Extraction
1. Turn on your 3DS and launch the **Homebrew Launcher**.
2. Locate and select the **CTGP-7 Offline Installer** from the list.
3. Follow the on-screen prompts to allow the application to extract and verify the core asset data on your SD card. 

### 3. Home Menu Forwarder (Optional but Recommended)
1. Once extraction finishes, open **FBI** on your 3DS.
2. Navigate to `SD` -> `CTGP-7` -> `cia/`.
3. Select `CTGP-7.cia` and choose **Install CIA**.
4. Press the Home button. You can now launch CTGP-7 directly from your 3DS Home Menu wrapper icon instead of booting Homebrew Launcher every time.

---

##  Troubleshooting

*   **Installer Fails/Freezes mid-way:** Ensure you have enough free space on your SD card. The console needs extra room to uncompress files during installation.
*   **Game Crashes on Launch:** Double-check that your *Mario Kart 7* base game is updated to v1.2. The mod will crash on boot if the base game is unpatched.
*   **Missing Textures/Tracks:** If tracks load completely blank or lock up your console, a file may have corrupted during transfer. Delete the `CTGP-7` folder from the root of your SD card and re-copy the clean offline files.

---

##  Community & Links
*   **Official Website:** [ctgp-7.github.io](https://github.io)
*   **Support Discord:** [Join the CTGP-7 Community](https://discord.gg)
