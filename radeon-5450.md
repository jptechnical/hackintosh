For OS X and macOS including High Sierra ATI Radeon 5450 needs the following edits in Config.plist:

FakeID: 0x68E01002 against ATI in config.plist>Devices ,
[√] Inject ATI in config.plist>Graphics
[Eulemur] as FB Name in config.plist>Graphics

I installed initially High Sierra Beta 3 with the previously created USB Installer and then updated the system to Beta 4 when I got notified about the new release.

On installation the Graphics display was in "Billions of Colors" and any "Finder use" caused the screen to show "bleeding colors' and "jittery screens". I had to install SwitchResX to change "Billions of colors" to "Millions of colors" to fix the Display problem.

http://www.madrau.com/srx_download/download.html
After install, clickon the monitor icon in task bar, choose millions of colors instead of billions in each monitor. tested OK
