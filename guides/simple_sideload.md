[ **[RU](https://github.com/itsflameee/jailed/blob/main/guides/simple_sideload_ru.md)** / **[EN](https://github.com/itsflameee/jailed/blob/main/guides/simple_sideload.md)** ]
# Simple Sideload Guide
> by its.flame's Jailed!

# Table of Contents
1. [Choosing a Sideload Method  ](https://github.com/itsflameee/jailed/new/main/guides#choosing-a-sideload-method)
2. [Recommendations from the its.flame's Jailed Team](https://github.com/itsflameee/jailed/new/main/guides#recommendations-from-the-itsflames-jailed-team) 
3. [Sideload Process ](https://github.com/itsflameee/jailed/new/main/guides#sideload-process) 

## Choosing a Sideload Method
> [!NOTE]
> The its.flame's Injected team is not affiliated with or the developer of SideStore, AltStore, Sideloadly, Impactor, iloader, or LiveContainer.  
> We do not claim ownership of their work. All information provided here is for instructional purposes only, to help achieve a convenient sideloading experience.

First, you need to decide which sideloading method you want to use. Below, we will help you choose the most suitable option.

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/sidestore.png?raw=true" width="20" height="20"/> [SideStore](https://github.com/itsflameee/jailed/blob/main/guides/sidestore.md)
> *SideStore is a fork of AltStore*

This is currently the best sideloading method available. It allows you to sideload and refresh app signatures directly on the device (on-device method).  
However, it requires the use of [LocalDevVPN](https://github.com/itsflameee/jailed/blob/main/guides/localdevvpn.md) during sideloading or signature refresh.

You may encounter compatibility issues on older devices (as of early February 2026, the latest version of SideStore supports iOS 14 and newer).  
LiveContainer also has a version with SideStore built in, allowing more efficient use of the 3-app limit imposed on free Apple IDs.

Choose this method if:
- You need on-device sideloading and app refresh
- You are interested in LiveContainer integration

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/altstore.png?raw=true" width="20" height="20"/> [AltStore](https://github.com/itsflameee/jailed/blob/main/guides/altstore.md)
This method is (or was) one of the most popular. It allows sideloading and app signature refreshing through a convenient on-device interface, but requires a PC or Mac with AltServer installed during installation or refresh.

Compatibility issues are unlikely, as AltServer allows installing older versions of AltStore, ensuring support for legacy devices  
(the its.flame's Jailed team has tested it on an iPhone 5s running iOS 12.5.7).

Use this method if:
- You need support for older iOS versions

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/sideloadly.png?raw=true" width="20" height="20"/> [Sideloadly](https://github.com/itsflameee/jailed/blob/main/guides/sideloadly.md)
This method is very popular due to its simplicity. To sideload an app, you only need to connect your device to a PC via cable, select an IPA file, and configure the sideloading options.

Use this method if:
- You do not need on-device sideloading or app refresh
- You want speed and simplicity

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/impactor.png?raw=true" width="20" height="20"/> [Impactor](https://github.com/itsflameee/jailed/blob/main/guides/impactor.md)
This method is very similar to Sideloadly.  
However, it is considered outdated and is recommended only for older iOS versions (for example, iOS 12).

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/iloader.png?raw=true" width="20" height="20"/> [iloader](https://github.com/itsflameee/jailed/blob/main/guides/iloader.md)
This method is also similar to Sideloadly and Impactor, but offers a more modern UI, better usability, and additional features such as Pairing File support and integration with SideStore and LiveContainer.

It also allows downloading SideStore and LiveContainer directly from within the installer.  
This is the official installation method for SideStore, and the its.flame's Jailed team recommends it.

Choose this method if:
- You want to install SideStore / LiveContainer / LiveContainer + SideStore
- You need built-in Pairing File (JitterBugPair) functionality

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/livecontainer.png?raw=true" width="20" height="20"/> [LiveContainer](https://github.com/itsflameee/jailed/blob/main/guides/sidestore.md)
LiveContainer is not a full sideloading method, but it allows running third-party applications inside a container.  
Make sure to review the limitations of this method in the SideStore & LiveContainer guide.

This method is recommended to be used together with SideStore.

Use it if:
- You need more than 3 apps on a free Apple ID
- You want built-in SideStore functionality

Based on the information above, choose the method that best suits your needs.

## Recommendations from the its.flame's Jailed Team

| Case | Recommended Method | Notes |
| ---- | ------------------ | ----- |
| iOS 14.0–16.6.1, iOS 17.0 | **TrollStore** | The most convenient method for these iOS versions, as it does not require app refresh. However, the its.flame's Jailed team does not currently provide TrollStore guides |
| iOS 14–26 | **LiveContainer + SideStore** or **SideStore** | Consider your personal requirements. In some cases, AltStore may be more convenient |
| Older iOS (iOS 14 and below) | **AltStore** | In some cases, jailbreaking may be a more reasonable option |
| Very old iOS (iOS 6 and below) | **Jailbreak** | On such old iOS versions, jailbreak is the most effective solution due to available rootful jailbreaks |
| Universal method | **Sideloadly**, **Impactor**, **iloader** | Use these if you only need to install an app without refreshing it (for iloader, use “Import IPA” instead of installing SideStore) |

## Sideload Process
To perform sideloading, choose a method above and click its title to open the corresponding guide.

### General Requirements:
- An iOS device supported by the chosen method
- A PC (with iTunes and iCloud installed from Apple’s website — Microsoft Store versions are not supported) or a Mac  
  (this requirement may vary depending on the installation method)
- An IPA file you want to install  
  (not required for SideStore and LiveContainer, as they only need iloader, or for AltStore, which only requires AltServer)
- An Apple ID (free Apple IDs are limited to 3 sideloaded apps)
