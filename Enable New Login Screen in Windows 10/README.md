<b><h1>  Enable New Login Screen in Windows 10  </h1></b>

Microsoft has put a new experimental Login Screen in Windows 10 builds which is not enabled by default. It features new rounded user pictures (avatars) along with a few other UI changes.

Windows_10_Secret_Login_Screen.png

You can activate it using following method:

1. In Registry Editor, go to following key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Authentication\LogonUI\TestHooks

2. In right-side pane, change value of Threshold to 1

That's it. It'll immediately enable the new login screen.

If you want to restore default Login Screen, change value of Threshold to 0 again.

PS: This new login screen is under development and contains many bugs, that's why its not enabled at the moment. Some people have faced problems after enabling this new login screen such as not able to log into Windows after restart or a clean boot.
