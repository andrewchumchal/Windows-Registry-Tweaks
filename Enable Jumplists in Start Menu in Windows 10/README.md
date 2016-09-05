<b><h1>  Enable Jumplists in Start Menu in Windows 10  </h1></b>

You can use following trick to enable jump list feature in Windows 10 Start Menu:

Windows_10_Start_Menu_Jumplist.png

1. In Registry Editor, go to following key:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced

2. In right-side pane create a new DWORD EnableXamlJumpView and set its value to 1

3. Restart your computer to take effect and enjoy jump lists in Start Menu of Windows 10.

To remove jump list feature from Start Menu, delete the new DWORD EnableXamlJumpView.
