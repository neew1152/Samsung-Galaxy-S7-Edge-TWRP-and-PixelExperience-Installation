# 📱 Install TWRP & PixelExperience (Android 11) on Samsung Galaxy S7 Edge

This guide will help you install **TWRP Recovery** and then flash **PixelExperience (Android 11)** on the Samsung Galaxy S7 Edge (**hero2lte**).

⚠️ **WARNING: This process will wipe all data on your device.**

* Internal storage is erased when formatting data in TWRP.

---

## 🔧 Requirements

* Samsung Galaxy S7 Edge (**hero2lte**)
* Samsung USB Driver: [Download here](https://developer.samsung.com/android-usb-driver)
* Odin Tool: [Download here](https://samsungodin.com/download)
* TWRP Image: [Download here](https://dl.twrp.me/hero2ltekor/twrp-3.7.0_9-0-hero2ltekor.img.tar.html)
* PixelExperience ROM (Android 11): [Download here](https://get.pixelexperience.org/changelog/hero2lte/PixelExperience_hero2lte-11.0-20210923-1630-OFFICIAL.zip)

---

## 🚀 Step 1 – Unlock Bootloader

1. Go to **Settings > About phone > Software information**
   → Tap **Build number** 7 times to unlock Developer Options.
2. Go to **Settings > Developer Options**
   → Enable **OEM Unlocking**.

---

## 💿 Step 2 – Install TWRP Recovery

1. **Enter Download Mode**

   * Power off the device
   * Press **Power + Volume Down + Home**
   * Press **Volume Up** to confirm

2. **Flash TWRP with Odin**

   * Open Odin on PC
   * Connect phone via USB
   * Load TWRP `.img.tar` into **AP slot**
   * Disable **Auto-Reboot**
   * Click **Start**

3. **Boot into TWRP**

   * When Odin says **PASS!**, force reboot:

     * Hold **Power + Volume Down** until screen turns black
     * Quickly press **Power + Volume Up + Home** to boot into TWRP

4. **TWRP Setup**

   * Tap **Keep Read Only**
   * Go to **Wipe > Format Data**
   * Reboot back into TWRP

---

## 📲 Step 3 – Install PixelExperience (Android 11)

1. **Swipe to Allow Modifications**
2. Go to **Wipe > Swipe to Factory Reset**
3. **Transfer ROM**

   * Copy `PixelExperience_hero2lte-11.0-20210923-1630-OFFICIAL.zip`
   * Place it in **Internal Storage** (`This PC\Galaxy S7 edge\Internal Storage`)
4. **Flash ROM**

   * In TWRP, go to **Install > /sdcard**
   * Select the PixelExperience `.zip` file
   * Swipe to confirm Flash
5. **Reboot System**

---

## ✅ Done!

Your Samsung Galaxy S7 Edge is now running **PixelExperience (Android 11)** 🎉

---

## 📚 Sources

* [Main Guide](https://xdaforums.com/t/basic-guide-to-installing-twrp-root-and-rom-via-odin-on-s7-amd-s7-edge.3872644/)
* [Buttons Guide](https://www.youtube.com/watch?v=fqDxBSRLEbQ)
* [PixelExperience Installation](https://www.youtube.com/watch?v=Iu4xbmvABsY)
