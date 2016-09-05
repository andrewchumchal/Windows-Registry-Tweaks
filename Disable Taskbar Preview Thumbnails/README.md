<b><h1>  Disable Taskbar Preview Thumbnails  </h1></b>

It is possible to disable taskbar thumbnails only for a group of opened windows i.e.multiple instances of the app. Once this is done, Windows 10 will show a list of windows instead of thumbnails. The list makes it easier to identify them from a group instead of mostly similar looking thumbnails. To do this, follow these instructions:

Go to the following Registry key:
HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Taskband
Create a new 32-bit DWORD value named NumThumbnails. Leave its value as 0. Note: If you are running 64-bit Windows 10, you still need to create a 32-bit DWORD value. disable taskbar preview thumbnails in Windows 10
Restart the Explorer shell or sign out and sign in back to Windows 10.

You are done! To restore the defaults, just delete the above mentioned NumThumbnails and ExtendedUIHoverTime values. Don't forget to restart the Explorer shell.