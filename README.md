# KillAppNow Ext

An improved, significantly optimized, and modern version of the original KillAppNow module. Refactored, stabilized, and updated to the latest LsPosed API 101 standards, supported by lead developer Hargriv (H-K-Systems).

---

## 📝 Official Changelog (v2.0)

This release consolidates all optimized branches into a single distribution hub:

### 📦 1. KillAppNow_Ext_vA13-15_Base.apk
* **Target:** Android 13, 14, 15 (OneUI 5.x - 7.x Legacy).
* **Changelog:**
  * Lowered the API level to 33 Android 13+
  * Added a hook for gesture navigation
  * Added vibration response
  * Corrected the behavior of the module on OneUI 7.0 Android 15 now it works as it should
  * The module signature has been changed to mine
  * The module versions have been increased so that the notification about the availability of an update from the author's official repository is not constantly displayed
  * ( KillAppNow_Ext_2.0_A13_15_OneUI5.x_7.x_API-Legacy89.apk )


### 📦 2. KillAppNow_Ext_vA16_Legacy_API89.apk
* **Target:** Android 16 (Early / Transition vendor builds).
* **Engine:** Legacy Xposed API 89 framework bridge.
* **Changelog:**
  * Toast notification
  * This module has localization options ( Toast notification and log notifications are currently in English, Ukrainian or France language )
  * Vibration feedback
  * And a 3-second delay before the app closes
  * Added protection on the main screen (now, when you are on the main screen and hold down the back button, the module does not kill any processes)
  * Added double vibration on the main screen as a sign that there is nothing to kill
  * ( KillAppNow_Ext_2.0_A16_OneUI8.x_API-Legacy89.apk )


### 📦 3. KillAppNow_Ext_vA16_Modern_API101.apk
* **Target:** Android 16+ / OneUI 8.0+.
* **Engine:** Modern isolated `libxposed` architecture (API 101.0.1).
* **Changelog:**
  * The module has been completely rewritten to work with the new modern LsPosed API 101
  * Toast notification
  * This module has localization options ( Toast notification and log notifications are currently in English, Ukrainian or France language )
  * Vibration feedback
  * And a 3-second delay before the app closes
  * Added protection on the main screen (now, when you are on the main screen and hold down the back button, the module does not kill any processes)
  *  double vibration on the main screen as a sign that there is nothing to kill
( KillAppNow_Ext_2.0_A16_OneUI8.x_API-101.apk )


---

## ☕ Support & Donations
If you appreciate the work put into optimizing and maintaining this project, consider supporting the developer:
* **PayPal:** [https://www.paypal.com/donate/?hosted_button_id=RY8JBBKVMX956](projecthksystems@gmail.com)

---

## 📜 Credits & Respect
This project is built upon the original work of the initial author (@samahmed https://github.com/samahmed/KillAppNow ). All initial ideas and core logic belong to them. This Extended version exists to keep the module alive, clean, and fully compatible with modern environments.

* **Original Idea & Base:** KillAppNow
* **Refactoring, Optimization & Maintenance:** Hargriv H-K-Systems

---

## 🛑 Signature Verification Warning
This repository is the only official distribution hub for **KillAppNow Ext**. Any APK downloaded from third-party Telegram channels with altered signatures will trigger a **Signature Conflict / Security Warning** in modern LSPosed managers. To receive seamless official updates, use only the original untouched builds from the Releases section.