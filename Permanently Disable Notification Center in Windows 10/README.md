<b><h1>  Permanently Disable Notification Center in Windows 10  </h1></b>

If you don't like the new Action Center in Windows 10, you can disable it using following method:

1. In Registry Editor, go to following key:

HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\Explorer

2. In right-side pane, create new DWORD DisableNotificationCenter and set its value to 1

3. Restart, log off or restart Explorer as given here to take effect and it'll completely disable Notifications and Action Center in Windows 10.

If you want to re-enable it, delete the new DWORD DisableNotificationCenter.
