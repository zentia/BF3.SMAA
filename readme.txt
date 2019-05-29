injectSMAA v1.1

Description
- adds "Subpixel Morphological Antialiasing" to an application
- is based on "injectFXAA" (written by "some dude")
- is supposed to work only with directx 9, directx 10, directx 11, x86 applications
- may be incompatible with any other form of antialiasing

More information at http://mrhaandi.blogspot.com/.

SMAA is a very efficient GPU-based MLAA implementation, capable of handling subpixel features seamlessly, and featuring an advanced pattern detection & handling mechanism.
http://www.iryoku.com/smaa/


Install
If the game uses DirectX 9, put all files from the d3d9 directory into the directory containing the game executable.
If the game uses DirectX 10/11, put all files from the d3d10 directory into the directory containing the game executable.


Uninstall
Remove the files.


Notes
You may need to run your applications as administrator (required to write the logfile).
Do not use this tool while playing on anti cheat enabled servers (may be detected as a cheating measure)!
Do not mix d3d9  and d3d10 the files.
Install the latest DirectX runtime.
A "log.log" file is created to log behaviour/ bugs. Look inside to get additional information.
If the "log.log" file is not created then you use the wrong "*.dll" or you put it into the wrong directory.
Try to put the files into different directories before saying it doesn't work.


Keys
PAUSE : Enable/Disable FXAA
PRINT SCREEN : Screenshot


Changelog

v1.1
-Fix: (d3d9) GTA4 AlphaTest issue
-Fix: (d3d9) GTA4 DepthStencil issue

v1.0
-Add: SMAA