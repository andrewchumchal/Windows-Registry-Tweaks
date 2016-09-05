<b><h1>  Stop Windows Update from Hijacking the Sleep/Shutdown Button  </h1></b>

If you’d like to manually create this hack, you can open up regedit.exe using the start menu search box and then browse down to the following key, creating the key if it doesn’t exist.

HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\WindowsUpdate\AU



Add a 32-bit DWORD value called NoAUAsDefaultShutdownOption with a value of 1. No reboot should be necessary.

Now our Sleep button should be back to the way it was, but if you wanted to use the Install Updates and Shut Down option, it’s still available via the shutdown menu:
