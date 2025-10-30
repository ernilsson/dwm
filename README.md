# dwm
This is my fork of DWM which builds on the original project by adding support for external events that 
cause updates to the UI. Each such event is dispatched from a non-UI thread and processed within the UI
thread. These changes are mainly just to get a battery status to appear in the DWM bar. I guess you 
could say I made a piece of suckless software suck a bit more!

Obviously, my personal preferences are also present in the configuration header file since I am running
this little project as my daily driver.

## Disclaimer
It goes without saying that all credit of DWM goes to the original authors at [https://suckless.org]!
