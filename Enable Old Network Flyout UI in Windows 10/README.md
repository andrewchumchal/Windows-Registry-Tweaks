<b><h1> Enable Old Network Flyout UI in Windows 10 </h1></b>

Microsoft has added a new fly-out for Network icon in Taskbar notification area. If you don't like the new UI, you can restore previous Windows 8/8.1 style Network sidebar using following method:

Windows_10_Network_Flyout_Change.png

1. In Registry Editor, go to following key:

HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Control Panel\Settings\Network

2. Now take ownership of Network key with the help of <a href="http://www.howtogeek.com/77878/take-ownership-of-or-assign-full-permission-for-a-registry-key-in-windows-7/">this guide</a>.

3. Now in right-side pane, change the value of DWORD ReplaceVan to as following:

0 - Default flyout
1 - To open Network Settings window
2 - To show Windows 8/8.1 style Network sidebar
