[ [RU](https://github.com/itsflameee/jailed/blob/main/guides/sidestore_ru.md) / **[EN](https://github.com/itsflameee/jailed/blob/main/guides/sidestore.md)** ]

# <img src="https://github.com/itsflameee/jailed/blob/main/icons/sidestore.png?raw=true" width="20" height="20"/> SideStore &  <img src="https://github.com/itsflameee/jailed/blob/main/icons/livecontainer.png?raw=true" width="20" height="20"/> LiveContainer
> Guide by its.flame's Jailed!

# Table of contents
1. SideStore — What is it?
2. Installing SideStore
3. LiveContainer — What is it?
4. Installing LiveContainer
5. Installing SideStore + LiveContainer
6. Sideload Process

# SideStore — What is it?
> *SideStore is a fork of AltStore*

SideStore is an iOS application that allows you to install apps on your device outside of the App Store using only your Apple ID.  
SideStore resigns apps using your personal development certificate and then uses a specially designed VPN  
( <img src="https://github.com/itsflameee/jailed/blob/main/icons/localdevvpn.png?raw=true" width="12" height="12"/> [LocalDevVPN](https://github.com/itsflameee/jailed/blob/main/guides/localdevvpn.md) ) to bypass iOS restrictions and install them on your device.

(Information taken from the [official SideStore GitHub repository](https://github.com/SideStore/SideStore))

The its.flame's Jailed team will help you understand SideStore, LiveContainer, and their installation process.

# Installing SideStore
To install SideStore, we recommend installing  <img src="https://github.com/itsflameee/jailed/blob/main/icons/iloader.png?raw=true" width="12" height="12"/> [iloader](https://github.com/itsflameee/jailed/blob/main/guides/iloader.md)  from the [official repository](https://github.com/nab138/iloader/releases), as this installation method is recommended by the developers of LiveContainer and SideStore and is considered official.

For a detailed guide on how to install [SideStore from an IPA file](https://github.com/SideStore/SideStore/releases), see the  [guide for sideloading via iloader](https://github.com/itsflameee/jailed/blob/main/guides/iloader.md).  If you are fine with automatic installation, continue with the instructions below.

> [!IMPORTANT]
> In the future, you may need to use a pairing file (at minimum for proper SideStore functionality, and possibly for third-party apps such as StikDebug, EnsWilde, and other on-device exploits/apps).
> To be able to correctly obtain a pairing file, you must set a passcode on your device. Without a passcode, obtaining a pairing file will not be possible!

After installing iloader, go to the **Apple ID** section on the left and sign in to your account to enable app signing via iloader.  
In the future, when launching iloader, it will be enough to press **“Sign in”** — re-entering your credentials will not be required  
(you may only need to enter a two-factor authentication code received on your Apple device).

Next, in the **Installers** section, select **SideStore (Stable)** or **SideStore (Nightly)** and wait for SideStore to be installed on your device.  
Additional actions may be required. If you have never sideloaded apps on this device before, or if you previously removed all sideloaded apps, you may need to approve sideloading in Settings.  
To do this, go to **Settings → General → VPN & Device Management → Your Apple ID**, and approve the apps there.

# LiveContainer — What is it?
LiveContainer is an app launcher that allows you to run iOS apps without actually installing them on your device.  
(Information taken from the [official LiveContainer GitHub repository](https://github.com/LiveContainer/LiveContainer))

We will use LiveContainer to avoid being a “hostage” to Apple’s limit of 3 active sideloaded apps, allowing you to load up to 30 apps at once and freely switch between them inside LiveContainer.

# Installing LiveContainer
To install LiveContainer separately, use any sideloading method convenient for you  
(most commonly AltStore, SideStore, or iloader).  
You can choose a method in the  
[its.flame's Jailed sideloading guide](https://github.com/itsflameee/jailed/blob/main/guides/simple_sideload.md).

As the IPA file, use  
[LiveContainer from the official repository](https://github.com/LiveContainer/LiveContainer/releases).

We also recommend considering installing **LiveContainer + SideStore**, as this solution is preferred in most cases. See below for details.

# Installing SideStore + LiveContainer
If you decide to install the combined version of LiveContainer with SideStore, follow the instructions below  
(the installation process is very similar to installing SideStore).

## Method 1 — clean installation
This method is identical to installing SideStore.

To install SideStore, we recommend installing  
<img src="https://github.com/itsflameee/jailed/blob/main/icons/iloader.png?raw=true" width="12" height="12"/> [iloader](https://github.com/itsflameee/jailed/blob/main/guides/iloader.md)  
from the [official repository](https://github.com/nab138/iloader/releases), as this installation method is recommended by the developers of LiveContainer and SideStore and is considered official.

> [!IMPORTANT]
> In the future, you may need to use a pairing file (at minimum for proper functionality of SideStore built into LiveContainer, and possibly for third-party apps such as StikDebug, EnsWilde, and other on-device exploits/apps).
> To be able to correctly obtain a pairing file, you must set a passcode on your device. Without a passcode, obtaining a pairing file will not be possible!

After installing iloader, go to the **Apple ID** section on the left and sign in to your account to enable app signing via iloader.  
In the future, when launching iloader, it will be enough to press **“Sign in”** — re-entering your credentials will not be required  
(you may only need to enter a two-factor authentication code received on your Apple device).

Next, in the **Installers** section, select **LiveContainer + SideStore (Stable)** or **LiveContainer + SideStore (Nightly)** and wait for LiveContainer to be installed on your device.  
Additional actions may be required. If you have never sideloaded apps on this device before, or if you previously removed all sideloaded apps, you may need to approve sideloading in Settings.  
To do this, go to **Settings → General → VPN & Device Management → Your Apple ID**, and approve the apps there.

You will now have LiveContainer with SideStore built in.  
To access SideStore, open LiveContainer and tap the SideStore icon at the top.

## Method 2 — installation via SideStore
If you already have SideStore installed and want to install LiveContainer by merging them into a single app, follow these steps:

1. Download the  
   [LiveContainer + SideStore IPA file](https://github.com/LiveContainer/LiveContainer/releases)  
   (in the LiveContainer repository it is usually named `LiveContainer+SideStore.ipa`, but this may change in the future).
2. Open  
   <img src="https://github.com/itsflameee/jailed/blob/main/icons/sidestore.png?raw=true" width="12" height="12"/> SideStore, making sure that  <img src="https://github.com/itsflameee/jailed/blob/main/icons/localdevvpn.png?raw=true" width="12" height="12"/> LocalDevVPN  is running.
3. Tap the **“+”** button and select the previously downloaded IPA file.
4. After successful installation, delete  <img src="https://github.com/itsflameee/jailed/blob/main/icons/sidestore.png?raw=true" width="12" height="12"/> SideStore.

# Sideload Process

## <img src="https://github.com/itsflameee/jailed/blob/main/icons/sidestore.png?raw=true" width="20" height="20"/> Via SideStore

### Using the <img src="https://github.com/itsflameee/jailed/blob/main/icons/emoji_icons/share.png?raw=true" width="15" height="15"/> Share button
1. Download the IPA file you need
2. Make sure that <img src="https://github.com/itsflameee/jailed/blob/main/icons/localdevvpn.png?raw=true" width="20" height="20"/> LocalDevVPN is running
3. If you are using LiveContainer+SideStore, make sure that SideStore is open (to do this, tap the SideStore icon in the top-left corner)
4. Open <img src="https://github.com/itsflameee/jailed/blob/main/icons/apple/com.apple.DocumentsApp.png?raw=true" width="12" height="12"/> **Files**
5. Open the required file, tap <img src="https://github.com/itsflameee/jailed/blob/main/icons/emoji_icons/share.png?raw=true" width="12" height="12"/> **Share**, and select <img src="https://github.com/itsflameee/jailed/blob/main/icons/sidestore.png?raw=true" width="12" height="12"/> SideStore  
   (if you are using SideStore+LiveContainer, select <img src="https://github.com/itsflameee/jailed/blob/main/icons/livecontainer.png?raw=true" width="12" height="12"/> LiveContainer)

### Via the app
1. Download the IPA file you need
2. Make sure that <img src="https://github.com/itsflameee/jailed/blob/main/icons/localdevvpn.png?raw=true" width="20" height="20"/> LocalDevVPN is running
3. If you are using LiveContainer+SideStore, open SideStore from the main LiveContainer menu by tapping the SideStore icon in the top-left corner.  
   The following steps are the same for both SideStore and LiveContainer+SideStore.
4. Tap the **“+”** button, select the previously downloaded IPA file, wait for the installation to complete, and the app will appear on the Home Screen.

---

## <img src="https://github.com/itsflameee/jailed/blob/main/icons/livecontainer.png?raw=true" width="20" height="20"/> Via LiveContainer

### Using the <img src="https://github.com/itsflameee/jailed/blob/main/icons/emoji_icons/share.png?raw=true" width="15" height="15"/> Share button
1. Download the IPA file you need
2. Make sure LiveContainer is closed or that the main menu is open (see screenshot below)

<img src="https://github.com/itsflameee/jailed/blob/main/screenshots/sidestore_guide_screenshot_1.PNG?raw=true" width="258" height="558"/>

3. Open <img src="https://github.com/itsflameee/jailed/blob/main/icons/apple/com.apple.DocumentsApp.png?raw=true" width="12" height="12"/> **Files**
4. Open the required file, tap <img src="https://github.com/itsflameee/jailed/blob/main/icons/emoji_icons/share.png?raw=true" width="12" height="12"/> **Share**, and select <img src="https://github.com/itsflameee/jailed/blob/main/icons/livecontainer.png?raw=true" width="12" height="12"/> LiveContainer.  
   After that, you will see the new app in the list.

### Via the app
1. Download the IPA file you need
2. Make sure the LiveContainer main menu is open (see screenshot below)

<img src="https://github.com/itsflameee/jailed/blob/main/screenshots/sidestore_guide_screenshot_1.PNG?raw=true" width="258" height="558"/>

3. Tap the **“+”** button in the top-left corner
4. Select the required file, after which the new app will appear in the list.

