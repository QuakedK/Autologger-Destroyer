# Autologger Destroyer
Autologger Destroyer disables almost all Windows Autologgers via the registry!

<img width="978" height="512" alt="image" src="https://github.com/user-attachments/assets/df1f6817-b38e-4bf3-a374-2dc3ae5951e5" />

![GitHub Release Downloads](https://img.shields.io/github/downloads/QuakedK/Autologger-Destroyer/total)

# #1 Usage
Autologger Destroyer is required to be ran with Nsudo to delete some Autologgers without premission issues. Learn more here -> [Autologger Docs](https://github.com/QuakedK/Scripting-Station/blob/main/System%20Docs/Windows%20Autologgers.md#acess-denied)

1. Download [Nsudo](https://github.com/M2TeamArchived/NSudo/releases/download/9.0-Preview1/NSudo_9.0_Preview1_9.0.2676.0.zip) (Offical Site) or the Standalone exe from [Downloads](https://github.com/QuakedK/Autologger-Destroyer/raw/refs/heads/main/Downloads/NSudoLG.exe)
2. Download [Autologger Destroyer](https://github.com/QuakedK/Autologger-Destroyer/releases/download/AutologgerDisabler/Autologger-Destroyer-V1.0.bat).
3. Open [NSudoLG.exe](https://github.com/QuakedK/Autologger-Destroyer/raw/refs/heads/main/Downloads/NSudoLG.exe) and Enable All Privileges then drop/drag [Autologger Destroyer](https://github.com/QuakedK/Autologger-Destroyer/releases/download/AutologgerDisabler/Autologger-Destroyer-V1.0.bat) into Nsudo then click run.

# #2 Revert
1. Open [Nsudo](https://github.com/QuakedK/Autologger-Destroyer/raw/refs/heads/main/Downloads/NSudoLG.exe) and Enable All Privileges.
2. Then type CMD in the Address Bar, then click run and paste the following commands.
```bat
reg import "C:\Autologger Destroyer Backup\AutologgerBackup.reg"
```
> [!NOTE]
> If Autologger Destroyer was ran multiple times, the backup folder will not be just ```C:\Autologger Destroyer Backup```. It will create a new backup folder with a timestamp like ```Autologger Destroyer Backup [01-22-2026_05-09]``` and you must replace the path like ```reg import "C:\Autologger Destroyer Backup [01-22-2026_05-09]\AutologgerBackup.reg"```.

# #3 Autologger Docs
[Autologger Docs](https://github.com/QuakedK/Scripting-Station/blob/main/System%20Docs/Windows%20Autologgers.md)  | Documentation Created by me.

[Autologger Disable Idea](https://www.youtube.com/watch?v=33mwGjUTphY) | Ancel Video, I got the idea from!
