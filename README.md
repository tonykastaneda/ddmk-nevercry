# DDMK NEVER CRY
At somepoint in 2024 either Capcom or the Steam Family Share update bunked the current version of DDMK for the retail version of the HD Collection. Luckily I was able to peace meal a solution for those banging there head against the wall trying to install DDMK 2.7.3 or really any version. Well hopefully you never have to cry again after this mod.

# DDMK
For more information on DDMK head over to the original repo [here](https://github.com/serpentiem/ddmk)  
To quickly see the complete feature set, See [Features](https://github.com/serpentiem/ddmk/wiki/Features) on the DDMK docs for a more detailed overview.


# Installation

Before anything if you have a save make sure to [create backups](#create-savegame-backups) in case this workaround breaks anything.

1. Download and install any and all of the pre reqs listed in this [video](https://www.youtube.com/watch?v=MAHKvElDCS8&lc=UgwY7iptsZnIIByvTYx4AaABAg)
    * [DirectX Redist (June 2010)](https://www.microsoft.com/en-us/download/details.aspx?id=8109)
    * [Visual C++ Redist 2015-2022 x86 and x64](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)

> [!TIP]
> Confused? Check out this [video](https://www.youtube.com/watch?v=1LL8Hna3FIc&t=2s)  

2. Do a hard reboot on your system VCRedist should have prompted you to do this based on your windows install but if not go a head and do it anyways

3. Download and extract the [latest release]() `BASED ON YOUR GPUS ARCHITECHTURE` into the your DMCHDC Local Directory. By default this is `C:\Program Files (x86)\Steam\steamapps\common\Devil May Cry HD Collection`

You should be able to boot the game normally now from either Steam or the games exe directly.

If you've installed the mod successfully, you'll get a welcome message the next time you start the game (as in the actual game, not the launcher).

<!-- ![welcome](welcome.png) -->
![welcome](https://user-images.githubusercontent.com/38213025/144748682-48dcba6a-f98e-4789-9570-4264f3858254.png)


## Whats The Difference Between 2.6 and 2.7.3

### Regarding 2.6

When trying to install DDMK the first time around I stumbled across this [video](https://www.youtube.com/watch?v=MAHKvElDCS8&lc=UgwY7iptsZnIIByvTYx4AaABAg) saddly none of it worked. But In the description he has a preconfig directory of 2.6 Beta 2 along with Downgraded exe files and tweaks that fix certain crashes in speicific parts of the game. More specifically a crash in Misison 19 When Virgil joins you in the 2nd phase of the Arkham fight. Because the `Single Actor` option needs to be on in order to use the style switching, Virgl `and by extension the doppleganger skill` don't work and/or crashes the game. Thus ProjectXsent has wrote in a pre config script that skips that phase in M19 all together.

> [!NOTE]  
> This config has seemingly been tested according to comments in the oringal video and has worked for me past M10 (6-25-24). Will update this section with a proper playthrough

### Latest Build 2.7.3 

I applied the same logic and files I did when tinkering around with ProjectXsent 2.6 preconfig to get the game to boot by simply swapping out the the 2.6 beta 2 files with the latest 2.7.3

> [!IMPORTANT]  
> 2.7.3 of this config has not been tested on anything past M2 (6-25-24) the style switch works so I assume so do the guns and melee weapons do as well. Have not tested either Doppleganger or the M19 Phase 2 fight. Will update this section with a proper playthrough


## Whats Installed

| Archive                                                                                                                    | File                                                                     |
| ---                                                                                                                        | ---                                                                      |
| [DDMK](https://github.com/serpentiem/ddmk)                                                                                 | All Files                                                                |
| [xdelta3](https://www.romhacking.net/download/utilities/928/)                                                              | xdelta3-3.0.11-x86_64.exe                                                |
| [dmc3_quick_drive](https://github.com/serpentiem/ddmk/releases/download/2.7nightly16/dmc3_quick_drive.zip)                 | diff_pI000_00_3                                                          |
| [Switch HUD](https://github.com/serpentiem/ddmk/releases/download/2.7nightly16/dmc3_quick_drive.zip)                       | id100.pac                                                                |
| [Goldberg Emulator](https://gitlab.com/Mr_Goldberg/goldberg_emulator/-/jobs/4247811310/artifacts/download)                 | steam_api.dll, steam_api64.dll, steam_appid.txt, disable_networking.txt  |
| [Switch HUD](https://github.com/serpentiem/ddmk/releases/download/2.7nightly16/dmc3_quick_drive.zip)                       | id100.pac                                                                |
| [ProjectXsent 2.6 Pre Config](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbjM2ZWhMR2hXRWo5Qlg1QURmVGZybWtud2xFUXxBQ3Jtc0tuUm5mTGJDd0o0S2dGbWtYdHNybkxDV3ZsR1c5RHp2RkJUcGpMdi1OUlBvNXVKVTk0bGxiWnFkUFk2LXVtQ0YyMlVfLUhXbGk0RE5sVDN0bTNMdFhoUlp0clRYdldHQ01nOEtFa2IzM1NnQVBXMzBIRQ&q=https%3A%2F%2Fwww.dropbox.com%2Fs%2Ficvwpqch2om5t26%3Fdl%3D1&v=MAHKvElDCS8)                                             | dmc1.exe, dmc2.exe, dmc3.exe, dmcLauncher.exe                            |



# Create Savegame Backups

Go to the savegame directory. By default this is `C:\Program Files (x86)\Steam\userdata\STEAM_ACCOUNT_ID\631510\remote`. Should be the only folder in userdata unless you have multiple steam accounts

If you don't know your `STEAM_ACCOUNT_ID`, you can find it here:
* In Steam hover over your profile photo in the top right corner and click on `Account Details` you should then find the ID directly under your username

Copy the following files to a secure and easily accessible location:

* `dmc1.sav`
* `dmc2.sav`
* `dmc3.sav`




# Credits

Serpentiem and his work on [DDMK](https://github.com/serpentiem/ddmk)  
ProjectXsent and the [Pre Configuration](https://www.youtube.com/watch?v=MAHKvElDCS8&lc=UgwY7iptsZnIIByvTYx4AaABAg)  
