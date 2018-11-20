[Home](/)
# Windows Quick Access

**Network settings:** *`ncpa.cpl`*

**Stored User Names and Passwords:** *`rundll32.exe keymgr.dll,KRShowKeyMgr`*

**Windows Updates (method 1):** *`control.exe /name Microsoft.WindowsUpdate`*
**Windows Updates (method 2):** *`ms-settings:windowsupdate`*

# Windows 10 Special Folders Quick Access

**Windos 10 Administrative Tools Folder:** *`shell:Common Administrative Tools`*

**Windos 10 Apps Folder:** *`shell:AppsFolder`*

**Windos 10 Control Panel Folder:** *`shell:ControlPanelFolder`*

**Windos 10 Printers Folder:** *`shell:PrintersFolder`*

**Windos 10 Start Menu Folder:** *`shell:Start Menu`*

**Windos 10 Startup Folder:** *`shell:Startup`*

**Windos 10 Startup Folder for all users:** *`shell:common startup`*

**Windos 10 Updates Folder:** *`shell:AppUpdatesFolder`*

**Windos 10 User Pinned Folder:** *`shell:User Pinned`*

**Windos 10 User Profiles Root Folder:** *`shell:UserProfiles`*

## Notes:
Windows 10 exposes all the user accessible folders using Windows Explorer through the command *"Shell"*, it is possible find the Windows special folder names examining the the *Name* value in the registry entries of the registry key *HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions*.
