<b><h1> Enable Old Battery Flyout UI in Windows 10  </h1></b>

You can use following method to disable the new Modern (Metro) style Battery fly-out and restore good ol' classic Battery info UI in Windows 10 Taskbar Notification Area (aka System Tray):

Windows_10_Battery_Flyout_Change.png

1. In Registry Editor, go to following key:

HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\ImmersiveShell

2. In right-side pane, create a new DWORD UseWin32BatteryFlyout and set its value to 1

That's it. It'll immediately disable the new Battery fly-out and restore classic UI in system tray.

If you want to restore new Battery fly-out, delete the new DWORD UseWin32BatteryFlyout.
