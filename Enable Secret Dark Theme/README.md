<b><h1> Enable Secret Dark Theme </h1></b>

Windows 10 comes with a hidden secret Dark theme mode which can be unlocked and tested in Modern (metro) apps:

Windows_10_Dark_Theme_Mode.png

1. In Registry Editor, go to following key:

HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Themes\Personalize

2. In right-side pane, create a new DWORD AppsUseLightTheme and leave its value to 0

3. That's it. Now you can enjoy dark UI in all modern apps including Settings app.

To restore default UI, delete the new DWORD AppsUseLightTheme.

PS: In previous testing builds of Windows 10, the DWORD was actually SystemUsesLightTheme which was replaced with AppsUseLightTheme in final version of Windows 10.

UPDATE: Now this dark theme feature is officially available in Settings app
