<b><h1> Disable Login Screen Background Image in Windows 10  </h1></b>

Microsoft has put the new "Hero" wallpaper as the background image of Login Screen in Windows 10. Interested people can disable or remove it using following method:



Default_Windows_10_Login_Screen.png

1. In Registry Editor, go to following key:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System

2. In right-side pane, create new DWORD DisableLogonBackgroundImage and set its value to 1

3. Restart your computer and it'll remove the background image from login screen.

If you want to restore Login Screen background image in future, delete the DWORD DisableLogonBackgroundImage.
