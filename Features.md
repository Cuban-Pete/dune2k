Features
================================================================================

1. Support for .ini file format

2. dune2000.cfg has been replaced with dune2000.ini

3. Fix for the "HelpURLError" caused by broken WOL installations

4. Disabled the registration dialog in WOL since the registration goes automatically on the first login

5. Raised the player limit for WOL games from 4 to 6

6. In-game messages are now shown for a longer time (3x longer)

7. Fixed up the original built in NoCD mode and made it configurable via dune2000.ini
 - [Options] ForceNoCD= (Yes/No)

8. Changed multiplayer variables
 - (LAN/WOL) InitialConnectTimeOut = 15sec (original = 60sec)

9. Added support for mouse wheel sidebar scrolling
 
10. All hotkeys are now changeable via dune2000.ini (the hex value from the microsoft site needs to be converted to decimal)
 - http://msdn.microsoft.com/en-us/library/windows/desktop/dd375731%28v=vs.85%29.aspx
 - http://www.binaryhexconverter.com/hex-to-decimal-converter
 - [Hotkeys] function= (virtual key decimal value)
 
11. Added support for 5 mouse buttons (they have no function by default, configurable via dune2000.ini)
 - VK_MBUTTON 0x04
 - VK_XBUTTON1 0x05
 - VK_XBUTTON2 0x06
 
12. Hotkey sidebar scrolling can be slowed down now, configurable via dune2000.ini
 - [Options] SlowSideBarScrolling= (Yes/No)

13. Added 4 new hotkeys for map scrolling, configurable via dune2000.ini
 - [Hotkeys] ScrollLeft= (virtual key decimal value) - default = numpad1 
 - [Hotkeys] ScrollDown= (virtual key decimal value) - default = numpad2 
 - [Hotkeys] ScrollRight= (virtual key decimal value) - default = numpad3
 - [Hotkeys] ScrollUp= (virtual key decimal value) - default = numpad5
 
14. Built-in high resolution patch, configurable via dune2000.ini
 - [Options] GameWidth=
 - [Options] GameHeight=
 - High res sidebar graphics: http://funkyfr3sh.cncnet.org/files/d2k/HighRes-sidebar.7z
 - High res backgrounds: http://funkyfr3sh.cncnet.org/files/d2k/HighRes-backgrounds.7z
 
15. All useful command line parameters are now configurable via dune2000.ini
 - [Options] MoviesEnabled= (Yes/No)
 - [Options] SoundsEnabled= (Yes/No)
 - [Options] SkipIntro= (Yes/No)
 - [Options] VideoBackBuffer= (Yes/No)

16. New command line parameter "-window" to run the game in window mode (won't work perfectly yet)
