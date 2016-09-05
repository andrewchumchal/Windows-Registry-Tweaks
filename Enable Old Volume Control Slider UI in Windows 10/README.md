<b><h1> Enable Old Volume Control Slider UI in Windows 10 </h1></b>

Microsoft has added a new horizontal UI for volume control slider in Windows 10 which is shown when you click on the Sound icon in Taskbar notification area. If you don't like the new UI, you can restore previous vertical volume control slider using following method:

Windows_10_Volume_Control_Slider_Change.png

1. In Registry Editor, go to following key:

HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\

2. Create a new key MTCUVC under CurrentVersion key.

3. Now in right-side pane, create new DWORD EnableMtcUvc and set its value to 0

If you want to restore new volume control UI, delete the DWORD EnableMtcUvc.
