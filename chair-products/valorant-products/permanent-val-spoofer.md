---
description: INCLUDES A TPM BYPASS!!
---

# PERMANENT VAL SPOOFER

<figure><img src="../../.gitbook/assets/permwoof_gif.gif" alt=""><figcaption></figcaption></figure>

## Perm Spoofer

You should do a clean reinstallation of windows, to clean up any traces and any ban logs that valorant generates in Windows

<details>

<summary>Clean Windows Reinstall</summary>

*
*
*
*
*
*
*

![](https://guides.moddingassociation.net/\~gitbook/image?url=https%3A%2F%2F4078172018-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fgxol57krZAOcrJxJpuhe%252Fuploads%252FMtPMNA3YweuK14Ad8mmL%252F1.png%3Falt%3Dmedia%26token%3D7ea2b1d3-73c7-4921-bcc1-65083a0eaf60\&width=300\&dpr=4\&quality=100\&sign=ee089106\&sv=1)

*

![](https://guides.moddingassociation.net/\~gitbook/image?url=https%3A%2F%2F4078172018-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fgxol57krZAOcrJxJpuhe%252Fuploads%252FfHyL7i7leWKloA1Rwysf%252F2.png%3Falt%3Dmedia%26token%3De4442a95-7934-4508-9435-c6afe83bd0fd\&width=300\&dpr=4\&quality=100\&sign=e7394187\&sv=1)

*

![](https://guides.moddingassociation.net/\~gitbook/image?url=https%3A%2F%2F4078172018-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fgxol57krZAOcrJxJpuhe%252Fuploads%252FMICN6U9QYJ6b5KF1umqs%252F3.png%3Falt%3Dmedia%26token%3D31e92311-eb49-4b53-813f-72744de1c605\&width=300\&dpr=4\&quality=100\&sign=81d3d493\&sv=1)

*

![](https://guides.moddingassociation.net/\~gitbook/image?url=https%3A%2F%2F4078172018-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fgxol57krZAOcrJxJpuhe%252Fuploads%252FIzLvU21O3stuq8OuPcrA%252F4.png%3Falt%3Dmedia%26token%3D5b620b5e-b710-46b2-b11c-04565a427ef0\&width=300\&dpr=4\&quality=100\&sign=d8e97ac4\&sv=1)

*

![](https://guides.moddingassociation.net/\~gitbook/image?url=https%3A%2F%2F4078172018-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fgxol57krZAOcrJxJpuhe%252Fuploads%252FF8HWGhxsHMKxkUEAPckB%252F5.png%3Falt%3Dmedia%26token%3Da168ac7a-1e1b-4f6e-b21e-b65b6bffe123\&width=300\&dpr=4\&quality=100\&sign=9a972511\&sv=1)

*
*
*

![](https://guides.moddingassociation.net/\~gitbook/image?url=https%3A%2F%2F4078172018-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fgxol57krZAOcrJxJpuhe%252Fuploads%252FrBDhZGE1Z0ZsEGaUdIda%252F6.png%3Falt%3Dmedia%26token%3D82867dc4-bb5d-4bfa-856b-fbc224d9ec70\&width=300\&dpr=4\&quality=100\&sign=762e0bdb\&sv=1)

*

![](https://guides.moddingassociation.net/\~gitbook/image?url=https%3A%2F%2F4078172018-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fgxol57krZAOcrJxJpuhe%252Fuploads%252FcKUyBmz4zLHvcJwmyaRF%252F7.png%3Falt%3Dmedia%26token%3Dbcd90db5-91ac-4273-9edf-6e10147e70dd\&width=300\&dpr=4\&quality=100\&sign=36ea56bf\&sv=1)

*
*

</details>

Disable any and all antivirus that is running on your computer, even in the background, you can use the ["Control Defender"](https://www.sordum.org/files/downloads.php?st-defender-control) tool to permanently disable your Windows antivirus (PASSWORD : sordum)

Disable Windows Update using [**WUB**](https://www.sordum.org/files/downloads.php?st-windows-update-blocker)

<details>

<summary>Bios Flash</summary>

#### &#x20;<a href="#tutorial" id="tutorial"></a>

1.
2.
3.

#### &#x20;<a href="#here-are-some-video-tutorials-for-flashing-the-bios" id="here-are-some-video-tutorials-for-flashing-the-bios"></a>

</details>

**After flashing, we must configure our bios:**

AMD BIOSINTEL BIOS

DISABLE TPM 2.0 (Trusted Platform Module)

DISABLE Trusted Computing

DISABLE Secure Boot **and restore/install all secure boot keys**

Disable CSM (Compatibility Support Module)

Disable SVM (CPU Virtualization) in your BIOS

After that, save the changes and exit your BIOS

**Then check that the changes have been made successfully:**

* In windows, Press WinKey + R and type **msinfo32** and press Enter. Check if the value for **Secure Boot State** is **OFF**
* Press WinKey + R and type **tpm.msc** and press Enter. It should say no compatible tpm is found

**If it's as expected, we can continue with the tutorial**

<details>

<summary>Spoofing PC</summary>

#### &#x20;<a href="#saving-your-old-hwid" id="saving-your-old-hwid"></a>

#### &#x20;<a href="#spoofing" id="spoofing"></a>

</details>

**To bypass TPM 2.0 / HVCI / SB, access our other tab called** VAN RESTRICTION

**To bypass TPM 2.0, access our other tab called TPM BYPASS**

### Additional Spoofing <a href="#additional-spoofing" id="additional-spoofing"></a>

If you are still getting banned even after following all the methods listed above, or if you want more security when spoofing to completely avoid a ban, follow the methods listed below

<details>

<summary>Spoofing your GPU (Optional)</summary>



</details>

<details>

<summary>Spoofing your monitor (Optional)</summary>



</details>

Remember to use [VAN:RESTRICTION](https://guides.moddingassociation.net/permanent-spoofer/van-restriction-bypass) BYPASS or [TPM BYPASS](https://guides.moddingassociation.net/permanent-spoofer/tpm-bypass) you'll be banned from valorant again!

<details>

<summary>Spoofing your network (Optional)</summary>

Some anticheats may ban your router's MAC address and various other aspects of your internet connection. It is recommended to use a VPN while playing, but remember, this is not mandatory.

Recommended VPNs

* ExpressVPN
* NordVPN
* Windscribe
* WARP (if the game has any VPN restrictions)

</details>

[PreviousModdingAssociation.net](https://guides.moddingassociation.net/)[NextVAN:RESTRICTION BYPASS](https://guides.moddingassociation.net/permanent-spoofer/van-restriction-bypass)

Last updated 2 hours ago

Perm Spoofer | MA - Guide
