<b><h1> Increase Taskbar Transparency Level in Windows 10 </h1></b>

By default, Windows 10 Taskbar comes with Aero glass transparency effect but the transparency level is not very high. With the help of following Registry tweak, you can increase transparency level of Windows 10 Taskbar and can add extra clear transparency effect to the Taskbar:

Registry_Tweak_Taskbar_Transparency_Windows_10.png

1. In Registry Editor, go to following key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced

2. In right-side pane, create new DWORD UseOLEDTaskbarTransparency and set its value to 1

3. Restart, log off or restart Explorer as given here to take effect and it'll make Windows 10 Taskbar more transparent.

If you want to restore Taskbar default transparency level in future, delete the DWORD UseOLEDTaskbarTransparency.
