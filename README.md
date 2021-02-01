# How-to-Permanently-Disable-Windows-Defender-on-Windows-10
How to Permanently Disable Windows Defender on Windows 10

If you want to disable Windows Defender then this video is for you, if you are installing Bidefender of other antivirus software, this should disable Windows Defender for you automatically. If you want to disable windows disable it manually then I will show you  how. 

------------------

Go to search "gpedt"

Next click to "edit group policy"

Computer Configuration / Administrative Templates / Windows Components / Windows Defender Antivirus

Look for turn off windows defender antivirus 

Select Enabled 

--------------------

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender

New,  DWORD (32-bit) Value and name it DisableAntiSpyware

Set the value from to 1

------------------------
