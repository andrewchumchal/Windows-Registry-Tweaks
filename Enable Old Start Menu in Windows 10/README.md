<b><h1>  Enable Old Start Menu in Windows 10  </h1></b>

Microsoft has replaced previous Windows 10 Start Menu with a new one in the latest Windows 10 build 9926 which is a little bit buggy and can't be resized. Luckily, the old Start Menu still exists in the OS. Interested people can enable the old resizable Start Menu in Windows 10 using following method:

New_Start_Menu_with_Live_Tiles.png

1. In Registry Editor, go to following key:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced

2. In right-side pane create a new DWORD EnableXamlStartMenu and leave its value to 0

3. Restart, log off or restart Explorer as given here to take effect and enjoy the old Start Menu in Windows 10.

To restore the new Start Menu, delete the new DWORD EnableXamlStartMenu.
