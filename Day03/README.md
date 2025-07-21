Here's a clean and structured version of your **Day03 notes** that you can copy into `Day03/README.md` before uploading to GitHub:

---

# 📘 Day 03 Notes: Installing VirtualBox & Kali Linux + Reboot Process

## 🧰 Tools Covered

* **VirtualBox** (Virtual Machine software)
* **Kali Linux** (Penetration Testing OS)

---

## ✅ Step 1: Install VirtualBox

### 🔹 For Windows:

1. Go to [https://www.virtualbox.org](https://www.virtualbox.org)
2. Download the **Windows hosts** installer
3. Run the installer and follow on-screen instructions
4. Accept network adapter prompts if they appear
5. Finish setup and launch VirtualBox

---

## ✅ Step 2: Download Kali Linux ISO

1. Go to [https://www.kali.org/get-kali/](https://www.kali.org/get-kali/)
2. Scroll to the **Installer Images** section
3. Download the **64-bit ISO** (e.g., `kali-linux-2024.2-installer-amd64.iso`)
4. Save it somewhere accessible (like your Downloads folder)

---

## ✅ Step 3: Create a New Virtual Machine in VirtualBox

1. Open **VirtualBox**
2. Click **New**
3. Name it something like `KaliLinux`
4. Type: `Linux`, Version: `Debian (64-bit)`
5. Set RAM to at least **2048 MB** (or more)
6. Choose **Create a virtual hard disk now**

### Hard Disk Settings:

* File Type: VDI (VirtualBox Disk Image)
* Storage: Dynamically allocated
* Size: Minimum **20 GB**

---

## ✅ Step 4: Attach Kali ISO and Install

1. With VM selected → Click **Settings**
2. Go to **Storage** tab
3. Click on **Empty → Disk icon → Choose a disk file**
4. Select the Kali Linux ISO you downloaded
5. Click **OK**

### Start the VM:

1. Click **Start**
2. Follow the Kali installation process:

   * Choose **Graphical Install**
   * Set language, region, and keyboard
   * Create a user and password
   * Configure disk (use entire disk → All files in one partition)

---

## 🔄 Reboot After Installation

1. After installation, it will ask you to **remove installation media**

   * Go to **Devices → Optical Drives → Remove disk from virtual drive**
2. Click **Continue** to reboot the system
3. Login using the user credentials you created

---

## ✅ You're Done!

You now have Kali Linux running inside VirtualBox. 🎉



