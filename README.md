# Android Emulation Stuff
## Stuff related to emulating Android
 
### In short I've been trying to find the 1 emulator for all my needs for years now. 
 Sadly, most of them have some kind of issue that causes problems at some point.
 Here I'll list emulators and what I've experienced with them, if at all.
 
 ##[LDPlayer](https://www.ldplayer.net/download/install)
 Worked really well for the first month to two, but after that performance became atrocious with constant application crashes and random slow-downs as if there was a memory leak.
 For some people it stays working great, but not for me. 
 Seems to also require Hyper-V.
 ##[Nox]()
 Performance-wise works pretty well, however on my system there is a very noticeable ~1ms delay on sound, as if using a bluetooth speaker. 
 After some time also started having performance issues like LDplayer, but it never got as bad as LD.
 ##[Bluestacks 5](https://www.bluestacks.com/download.html)
 Resident adware emulator, I can't even install it but apparently its the best for Blue Archive. 
 DO NOT USE BLUESTACKS X.
 ##[Genymobile](https://www.genymotion.com/product-desktop/download/)
 Ran FGO pretty well for the short time I used it but it could not run Blue Archive (Android 9)
 It also does not support ARM out of the box so you have to use something like [this]()
 Also, its basically VirtualBox with some neat features for Android emulation.
 Requires an account, has features locked behind a subscription.
 ##[Windows subsystem for Android]() 
 This is an official way to run Android apps on Windows, requires Hyper-V AND VBS which for me made it impossible to use as I use RyzenMaster to Overclock my CPU and for some reason it doesn't work when VBS is enabled.
 Ran FGO pretty poorly (might've been caused by it downloading files).
 ##[Google Play Games for Developers](https://dl.google.com/tag/s/appguid=%7BC601E9A4-03B0-4188-843E-80058BF16EF9%7D&appname=GPG_Developer_Emulator_Stable&needsadmin=true&ap=prod/play/games/Install-GooglePlayGames-DeveloperEmulator-Stable.exe)
 The official google emulator(?) for andorid. Requires Hyper-V and VBS.
 The linked version should allow sideloading, the consumer version does not allow sideloading and requires the game to be compatible with it.
 From the little research I did neither Blue Archive nor Fate / Grand Order are compatible so I didn't test it.
 ##[MEmu](https://www.memuplay.com/)
 The performance was pretty ok, but the biggest issue I've had is transferring files into it and actually moving the files within the system. 
 Pretty much caused me not to use it due to how big of a pain in the ass actually setting it up was.
 ##[MumuPlayer](https://www.mumuplayer.com/index.html)
 Not tested yet.
 ##Waydroid [Linux Only]
 I haven't tried this one much outside of 1 week that I happened to be running linux but it worked perfectly with Fate / Grand Order.
 Everyone who used it says its the best.
 ##[QEMU]()
 It seems to have no GUI but is supposed to have better performance than using VirtualBox on its own.
 I'm not good at using terminals to interact with software so I gave up.
 ##[VirtualBox](https://www.virtualbox.org/wiki/Downloads)
 Haven't actually tried emulating Android on it, and the only reason it's even here is beacuase of BlissOS which I couldn't get running but maybe you can..
 