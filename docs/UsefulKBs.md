[Home](/)
# Useful KBs

## Office

**[Uninstall Office from a PC](https://support.office.com/en-us/article/uninstall-office-from-a-pc-9dd49b83-264a-477a-8fcc-2fdf5dbf61d8)** *`The following steps describe how to uninstall Office products on a PC. Uninstalling Office only removes the Office applications from your computer, it doesn't remove any files, documents, or workbooks you created using the Office apps.You can't uninstall an individual app such as Word or Publisher that's included as part of your Office Suite installation. The only way to uninstall an individual app is if you purchased it as a stand-alone version.`*
> **[Easy fix tool](https://aka.ms/diag_officeuninstall)**
>
> **[Manually uninstall Office](https://support.office.com/en-us/article/manually-uninstall-office-4e2904ea-25c8-4544-99ee-17696bb3027b)**

**[KB971058](https://support.microsoft.com/en-us/help/2212902/unexpected-autodiscover-behavior-when-you-have-registry-settings-under):** *`Unexpected Autodiscover behavior when you have registry settings under the \Autodiscover key`*
## Operating System

**[KB324737](https://support.microsoft.com/en-us/help/324737/how-to-turn-on-automatic-logon-in-windows):** *`How to turn on automatic logon in Windows`*
> **_Registry key:_** *HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon*
>
> **_AutoAdminLogon:_** *1 (REG_SZ)*
>
> **_DefaultUserName:_** *username (REG_SZ)*
>
> **_DefaultPassword:_** *password (REG_SZ)*

**[KB971058](https://support.microsoft.com/en-us/help/971058/how-do-i-reset-windows-update-components):** *`How do I reset Windows Update components?`*

**[KB4096063](https://support.microsoft.com/en-us/help/4096063/new-wmi-arbitrator-behavior-in-windows-server):** *`New WMI arbitrator behavior in Windows Server 2012 R2, Windows Server 2016, and Windows Server 2019`*

**[KB842715](https://support.microsoft.com/en-us/help/842715/overview-of-problems-that-may-occur-when-administrative-shares-are-mis):** *`Overview of problems that may occur when administrative shares are missing`*

**[KB842715](https://support.microsoft.com/en-us/help/12445/windows-keyboard-shortcuts):** *`Keyboard shortcuts in Windows`*

**[KB3064434](https://support.microsoft.com/en-us/help/3064434/windows-update-hangs-and-new-updates-are-uninstalled-after-a-restart):** *`Windows Update hangs and new updates are uninstalled after a restart`*
> Locate the following subkey: **_HKLM\System\CurrentControlSet\Services\TrustedInstaller_**
>
> Right-click the **_TrustedInstaller key, and then click Permissions_**
>
> Grant the **_Full Control user right to the Administrators group_**
>
> Change the **_BlockTimeIncrement_** value to 2a30 (Hexadecimal).

**[KB2509192](https://support.microsoft.com/en-us/help/2509192/clientname-and-sessionname-enviroment-variable-may-be-missing):** 
*`Clientname and Sessionname enviroment variable may be missing`*
> When connecting remotely with Remote Desktop Connection, the environment variables **_CLIENTNAME_** and **_SESSIONNAME_**
> are added to each process that is started.
>
> If you set the **_Folder Option "Launch folder windows in a separate process"_** and later launch an application
> from an additional Explorer window, the application will not see these additional environment variables.

**[KB3064434](https://support.microsoft.com/en-us/help/2533930/duplicate-folders-may-appear-after-enabling-folder-redirection):**
*`Duplicate folders may appear after enabling Folder Redirection`*
> When redirecting a user profile folder or folders using Group Policy,
> if the option "Move the contents of *folder* to the new location" is not selected
> there will be duplicate folders created in a user profile:
> one pointing to the redirected location and one on the local hard drive.
> Unless this option is selected, a duplicate link will be left behind, even when that folder is completely empty.
>
> **_This behavior is by design._**
>
> **_Local copies of the user profile folder(s) may be safely deleted if they are empty._**

**[KB929852](https://support.microsoft.com/en-us/help/929852/guidance-for-configuring-ipv6-in-windows-for-advanced-users):**
*`Guidance for configuring IPv6 in Windows for advanced users`*
> Windows Vista, Windows Server 2008, and later versions of Windows implement RFC 3484
> and use a prefix table to determine which address to use when multiple addresses are available for a Domain Name System (DNS) name.
> By default, Windows favors IPv6 global unicast addresses over IPv4 addresses.
> It is common for IT administrators to want to disable IPv6.
> This is often because of some unknown, networking-related issue, such as a name resolution issue.
> **_Important Internet Protocol version 6 (IPv6) is a mandatory part of Windows Vista and Windows Server 2008 and newer versions._**
> **_We do not recommend that you disable IPv6 or its components. If you do, some Windows components may not function._**
> **_We recommend that you use “Prefer IPv4 over IPv6” in prefix policies instead of disabling IPV6._**

**[KB4022522](https://support.microsoft.com/en-us/help/4022522/dcom-event-id-10016-is-logged-in-windows-10-windows-server):**
*`DCOM event ID 10016 is logged in Windows`*
> **_These 10016 events are recorded when Microsoft components tries to access DCOM components without the required permissions._**
> **_In this case, this is expected and by design._**
> A coding pattern has been implemented where the code first tries to access the DCOM components with one set of parameters.
> If the first attempt is unsuccessful, it tries again with another set of parameters.
> The reason why it does not skip the first attempt is because there are scenarios where it can succeed.
> In those scenarios, that is preferable.

**[KB17588](https://support.microsoft.com/en-us/help/17588/windows-fix-problems-that-block-programs-being-installed-or-removed):**
*`Fix problems that block programs from being installed or removed`*
> What it fixes:
>
> Corrupted registry keys on 64-bit operating systems
>
> Corrupted registry keys that control the update data
>
> Problems that prevent new programs from being installed
>
> Problems that prevent existing programs from being completely uninstalled or updated
>
> Problems that block you from uninstalling a program through Add or Remove Programs (or Programs and Features) in Control Panel
>
> Runs on Windows 7, Windows 8, Windows 8.1, Windows 10

**[KB4490414](https://support.microsoft.com/en-us/help/4490414/windows-server-update-services-best-practices):**
*`Windows Server Update Services Best Practices`*
> This article suggests best practices that can help you avoid configurations that experience poor performance because of design or configuration limitations in Windows Server Update Services (WSUS).


**[KB894199](https://support.microsoft.com/en-us/help/894199/software-update-services-and-windows-server-update-services-2020):**
*`Description of Software Update Services and Windows Server Update Services changes in content for 2020`*
> This article applies only to releases on the Windows Update website. This article does not apply to security releases for products that are not supported by Windows Update.
>
> This article is intended for use by administrators of Windows Server Update Services (WSUS), Windows Update, and Microsoft Update services. This article contains a list of content changes that have been made available on the second Tuesday of every month for WSUS, Windows Update, and Microsoft Update. Administrators can use this list both as a quick reference to content changes that have been made during routine synchronizations and as an explanation of these changes.

**[KB4469275](https://support.microsoft.com/en-us/help/4469275/introduction-to-the-account-lockout-and-management-tools):**
*`This article introduces Account Lockout and Management Tools`*
> https://www.microsoft.com/download/details.aspx?id=18465
>
> This set of tools helps you manage accounts and troubleshoot account lockouts.
