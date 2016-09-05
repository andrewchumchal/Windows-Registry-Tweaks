<b><h1> Enable Old Tray Clock and Calendar in Windows 10 </h1></b>

You can use following method to disable the new Modern (Metro) style Clock and Calendar UI and restore good ol' classic Date/Time UI in Windows 10 Taskbar Notification Area (aka System Tray):

Windows_10_Calendar_Flyout_Change.png

1. In Registry Editor, go to following key:

HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\ImmersiveShell

2. In right-side pane, create a new DWORD UseWin32TrayClockExperience and set its value to 1

That's it. It'll immediately disable the new Clock and Calendar UI and restore classic UI in system tray.

If you want to restore new Clock UI, delete the new DWORD UseWin32TrayClockExperience.
