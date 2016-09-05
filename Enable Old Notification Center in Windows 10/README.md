<b><h1>  Enable Old Notification Center in Windows 10  </h1></b>

Microsoft has updated Action Center (or Notification Center) UI in Windows 10. Now it opens as a sidebar and contains new quick action switches.

Following method will allow you to disable this new UI and restore previous fly-out UI of Action Center:

Windows_10_Action_Center_UI_Change.png

1. In Registry Editor, go to following key:

HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\ImmersiveShell

2. In right-side pane, change value of UseActionCenterExperience DWORD to 0

3. Restart, log off or restart Explorer as given here to take effect and it'll disable the new Action Center UI.

If you want to restore new UI, change value of UseActionCenterExperience DWORD to 1 again.
