---
icon: message-bot
---

# ASSIST TOOL

<figure><img src="../.gitbook/assets/assist tool.png" alt=""><figcaption></figcaption></figure>

{% content-ref url="../" %}
[..](../)
{% endcontent-ref %}

## Step 1

C++ Redistributable packs are installed using this > [link](https://aka.ms/vs/17/release/vc\_redist.x64.exe)

## Step 2

DirectX Runtime is installed using this [link](https://www.microsoft.com/en-us/download/details.aspx?id=35)

## Step 3

Microsoft DotNet is installed using this [link](https://aka.ms/dotnet-core-applaunch?missing\_runtime=true\&arch=x86\&rid=win10-x86\&apphost\_version=6.0.25)

## Step 4

Be sure Memory Integrity is turned off by doing the following: Windows Security -> Device Security -> Core Isolation -> Memory Integrity, turn it off and restart PC

## Step 5

If Riot Vanguard anti cheat is installed, it is recommended to remove it

## Step 6

Be sure to turn off any anti-viruses, as they will interfere with injection and even the injector in general, we recommend using Defender Control



### Injection instructions



Be sure that the game is closed

Open loader, enter your key and press enter to inject

After loader says "loaded success", let it close and open game

Let game load up, and proceed as normal, you should hear a beep after it is finished injecting.

Press Insert on your keyboard to open/close menu and such, proceed to use it

If a bsod occurs, reinstall the c++ redistributable and directx runtime then restart your pc again before loading the tool.



### Issues & fixes

### Common Issues <a href="#common-issues" id="common-issues"></a>

<details>

<summary>How to enable Virtualization</summary>

To enable virtualization, please search on Google for "How to enable virtualization on \[your motherboard name]." If you are unsure about your motherboard name, you can find it by following these steps:

Open the Run dialog by pressing the Windows key + R. Type "msinfo32" in the Run window and press Enter. The Windows System Information overview will open, and you will find your motherboard information specified next to "Baseboard Manufacturer."

#### Virtualization for Intel Users: <a href="#virtualization-for-intel-users" id="virtualization-for-intel-users"></a>

Once in your BIOS settings, head over to the advanced tab and select CPU configuration.

From there, go to Intel Virtualization Technology, and enabled it. Save changes and exit.

Your BIOS settings may differ depending on your manufacturer.

#### Virtualization for AMD Users: <a href="#virtualization-for-amd-users" id="virtualization-for-amd-users"></a>

Once in your BIOS settings, head over to the advanced tab and select CPU configuration.

From there, go to SVM Mode, and enabled it. Save changes and exit.

Your BIOS settings may differ depending on your manufacturer.

</details>

<details>

<summary>How to disable Hyper V</summary>

1. Press the **Win + R** key to open the **Run** dialog.
2. Type **control** and click **OK** to open the **Control Panel.**
3. In the **Control Panel,** click on **Programs**.
4. Next, click on **Programs and Features.**
5. In the left pane, click on **Turn Windows features on or off**
6. In the Windows Features dialog, locate **Hyper-V.**
7. Uncheck the **Hyper-V** option to disable the feature.
8. Next, scroll down and locate the **Virtual Machine Platform** and **Windows Hypervisor Platform** options.
9. Unselect both options and click **OK**.
10. Windows will uninstall Hyper-V and other features from your system.
11. Once done, restart your PC to apply the changes.

</details>

<details>

<summary>Missing VCRuntime140_1dll</summary>

You can download the runtime [here](https://aka.ms/vs/17/release/vc\_redist.x64.exe).

</details>

<details>

<summary>How to disable Win Defender</summary>

Here's how to disable your real time protection without downloading anything until the next time you restart your PC.

Open Start. Search for PowerShell, right-click the top result, and select the Run as administrator option.

Type the following command to disable Microsoft Defender Antivirus real-time protection and press Enter:

`Set-MpPreference -DisableRealtimeMonitoring $true`

#### Alternatively do the following: <a href="#alternatively-do-the-following" id="alternatively-do-the-following"></a>

**WIN 10 TURORIAL:**

[**https://youtu.be/NtgVXXbDU8A?si=5QoejTHVH8DccvF6**](https://youtu.be/NtgVXXbDU8A?si=5QoejTHVH8DccvF6)

**WIN 11 TURORIAL:**

[**https://youtu.be/v8-ikrGijTs?si=evE13gVakgFAzQNB**](https://youtu.be/v8-ikrGijTs?si=evE13gVakgFAzQNB)

</details>

### Bluescreens <a href="#bluescreens" id="bluescreens"></a>

<details>

<summary>MEMORY MANAGEMENT Blue screen</summary>

1. In the search box on the taskbar, type **regedit**, then select **Registry Editor** (Desktop app) from the results.
2. Travel to this path: HKEY\_LOCAL\_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management
3. Create a DWORD Value with the name being: **FeatureSettingsOverride**
4. Create a DWORD Value with the name being: **FeatureSettingsOverrideMask**
5. Set both of these to equal 3.
6. Restart PC.

</details>

<details>

<summary>SYSTEM SERVICE EXEMPTION Blue screen</summary>

This issues has to do with hyper v being enabled on your PC

Please go to the [Virtualization](https://persa.gitbook.io/persa/call-of-duty/issues-and-fixes#how-to-enable-virtualization) & [Hyper V](https://persa.gitbook.io/persa/call-of-duty/issues-and-fixes#how-to-disable-hyper-v) fix page to see how to disable Hyper V completly on your PC.

</details>

<details>

<summary>KERNAL_SECURITY_FAILURE_CHECK Blue screen</summary>

This bluescreen has to do with riot client or any other anti-cheat on your pc please uninstall them

[ESEA](http://www.uninstallhelps.com/how-to-uninstall-esea-client-by-e-sports-entertainment1.html) Anti-cheat

[Riot Vanguard](https://support-valorant.riotgames.com/hc/en-us/articles/360044648213-Uninstalling-and-Disabling-Riot-Vanguard) Anti-cheat

[EAC](https://www.youtube.com/watch?v=SHZqc02Urfc) Ant-cheat

[Battleeye](https://viraltalky.com/how-to-uninstall-battleye-guide/) Anti-cheat

[FaceIT](http://www.uninstallhelps.com/how-to-uninstall-faceit-1-0-20.html) Anti-cheat

</details>

### Other <a href="#other" id="other"></a>

<details>

<summary>Understanding Bans</summary>

Perm Bans/Shadow Bans/HWID Bans/Flag

**Cheat Detection:**

Before we get into this we need to understand what a cheat being detected means when a cheat gets detected all users will be banned it will not be just you please don't throw this work around in cheat servers as this word holds alot of value and reputation for a cheat provider. Remember aswell you are cheating in a game with an anti-cheat expect to be banned/shadowbanned.YOU ARE CHEATING MY GUY take the ban hop on a new acc , spoof and carry on with life.

**Permanent Ban:**

This means that account is gone kiss it goodbye there could be any amount of reasons that you could have been permanently banned i.e. You not spoofing correctly while hwid banned and going to play the game, a cheat gets detected, you get manually banned or you were just cheating to much and they gave you the harshest punishment.

**Shadow Ban/LIMITED MATCHMAKING:**

This means that you will not be able to play the game for 1-2 weeks usually gets lifted between 7-14 days THERE IS NO WAY TO UNSHADOWBAN AN ACC you just need to wait till they finish reviewing your account or we unlink your shadowbanned account.**Reasons for limited matchmaking:**

* Extreme or Repeated Violations
* Spoofing
* Circumventing Security
* Cheating/Modding/Hacking
* Pirated Content
* Unsupported Peripheral Devices and Applications
* Boosting
* Glitching
* Offensive Behaviour
* Griefing
* Improperly Obtained DLC
* Decompiling or Reverse Engineering of Game Data
* Malicious Reporting

</details>

<details>

<summary>Game crashing fix</summary>

If you are still experiencing crashing issues or “cheat not hooking, error 3” please try to:

Locate your game directory and delete "cod.exe" and "cod22.exe"once you do that it will download a new exe. After deleting the file, please run “Scan and repair” for Battlenet or “Verify game files” if you are on Steam. This will save you the time of deleting the full game and having to reinstall.

**Steam:**

`C:\Program Files (x86)\Steam\steamapps\common\Call of Duty HQ`

**Battlenet:**

`C:\Program Files (x86)\Call of Duty_retail_`

If that does not work for you then you will need to use **REVO UNINSTALLER** and uninstall the game and redownload.

**REVO UNINSTALLER**

[https://www.revouninstaller.com/revo-uninstaller-free-download/](https://www.revouninstaller.com/revo-uninstaller-free-download/)

* Get the free version
* Then uninstall the game and Battlenet or Steam whichever one you use
* Then restart pc
* Download the game and Battlenet or Steam again
* That should fix the CRASHING or BSOD issue

</details>

<details>

<summary>Delay Disconnects</summary>

This is not a method to not get disconnected. It is unpreventable. There is no way to not get disconnected.

This is how i play not to not get Dc'd but to prolong the time you can play on the acc while extend by days and even weeks if followed correctly.

What is **DC** or being **Disconnected** mean?

* Being disconnected from the game mean you got kicked from the game for either being reported by alot of players or you are on a new account (which is why you need an aged acc) beaming and playing like a streamer so of course they will know you cheating, it's also used as another way to prevent smurfing.

<!---->

* No, its not only just cause you are cheating in the game legit players have disconnected and even permanently banned. You can check Tiktok, Youtube, Reddit & Steam if you need evidence to see for your self Activision are just cunts.

<!---->

* A message will be displayed " Player kicked." that and only that message means that you have been disconnected. Not Server Disconncted or any of the sort that has to do with ur connection once you have been disconnected you are instantly shadowbanned here is what the dialog will look like.

So now that we understand what being disconnected means, how can we delay it?

To delay it, you'll need a well-aged account. The account level doesn't matter much. I've leveled up level 1 aged accounts to level 250 before experiencing disconnection. The account just needs to have at least 20,000 kills in either Modern Warfare 2019/Warzone Caldera or Modern Warfare 2/Warzone 2.0. You can use a fresh Battle.net account to link to the aged account, and the platform (Battle.net/Steam) doesn't matter. It all depends on how you play.

Now, let's get to the important details. You need to be a decent player who can engage in fights, read situations, and move well. You don't need to be as skilled as me, but you should be able to outplay opponents and appear legitimate. This is crucial to playing on any account for an extended time, even when you can see enemies through walls and never miss shots. Most cheaters play like bots with no movement, and that's why they need cheats. It's easy to spot a cheating bot, so our goal is to make the killcam look as legitimate as possible.

Now, let's talk about settings. We're not raging. The key to avoiding detection is not setting your aimbind key to the key you use to aim in. This would make you automatically lock onto the next person closest to you after downing someone, and we don't want that. Here are the settings: The aimbind key must match the key you use to shoot, so it only locks when you're shooting at someone. Set the aimbot field of view (fov) to between 5-8 fov, and the smoothness between 7-20. Lower smoothing makes the lock-on more abrupt. Keep the distance at least 150m, so you don't accidentally lock onto players out of cover if you forget to stop shooting. Set the aimlock to "any" or, in tight situations, use an override key for headshots. Only use the override key when necessary. No recoil can be used, but tone it down to 50-75%.

Visuals are up to you. You can use a UAV, walls, or radar, and the range can cover the whole map. It's your preference. Personally, I stay about 100m further than my aimbot.

Don't use exploits like long melee, clan tags, super slide, vehicle fly, airstrike, etc., as these are things normal players can't do.

Don't use the unlock all feature for extravagant items, especially on low-level accounts. It will raise suspicion. Stick to normal camos if needed.

When starting out, it's okay to die and not get many kills, especially on low-aged accounts. Dying is part of the game, and you don't need to prove anything to anyone. Avoid extreme situations that make you look suspicious. Take the death, come back, and try again.

For kills, start with at least 5 kills, then gradually increase to 10 kills or below. Once your games are complete, proceed with two games at 15 kills and two games at 20. This method should work, and you can become more aggressive.

Don't play for extended hours continuously. Limit your playtime to around 7 hours, as playing longer accumulates more reports. Take a break for an hour or two before returning to play.

If your account gets shadowbanned, wait it out for a week and then continue the process. You'll effectively "bypass" the disconnection system.

I AM NOT SAYING THIS WILL WORK FOR EVERYONE JUST PEOPLE ASK ME AND I THOUGHT ID LET YALL KNOW MY METHODS OF HOW I HAVE PLAYED AND KEEP MY ACCS FOR WEEKS SINCE THE REBIRTH DAYS.

</details>



