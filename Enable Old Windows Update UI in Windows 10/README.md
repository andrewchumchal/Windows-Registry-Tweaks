<b><h1>  Enable Old Windows Update UI in Windows 10  </h1></b>

Microsoft has also updated Windows Update UI in the latest Windows 10 build 9926 and some people are facing problems with this new UI.

Interested people can disable this new Windows Update UI and bring back the old UI using following method:

Windows_10_Update_Progressbar_Status.png

1. In Registry Editor, go to following key:

HKEY_LOCAL_MACHINE\Software\Microsoft\WindowsUpdate\UX

2. In right-side pane, change value of IsConvergedUpdateStackEnabled DWORD to 0

That's it. It'll immediately disable the new Windows Update UI.

If you want to restore new Windows Update UI, change value of IsConvergedUpdateStackEnabled DWORD to 1 again.
