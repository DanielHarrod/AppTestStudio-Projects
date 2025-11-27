# AppTestStudio-Projects

Projects created with https://github.com/DanielHarrod/AppTestStudio

Run the projects or use them for inspiration.

## System Setup:
### Monitor
Running the projects will need to match the monitor resolution that they were created under.
AppTestStudio currently does not suppport monitor scaling, set monitor scaling to 100% on the monitor that the application will be running under.
#### Recommended Monitor Settings
Windows -> System -> Display -> (Pick the monitor the target app will be running) -> Scale & Layout -> Scale -> 100%

### Power
Scripts can be run 24/7 or are scheduled day and nite.
AppTestStudio takes periodic screenshots, this requires the monitor to be on.  If the monitor is sleeping, windows stops updating the screen. 

#### Recommended Power Settings 
Windows -> System -> Power -> Plugged in -> Turn My screen off after -> Never

Windows -> System -> Power -> Plugged in -> Make my device sleep after -> Never

Windows -> System -> Power -> Plugged in -> Make my device hibernate after -> Never

### Minimizing Target Application
AppTestStudio takes periodic screenshots, but Windows is optimized to not update graphics when an app is minimized.

#### Recommended suggestions.
The target application can be off screen for those that support window mode, such as moved to the bottom or left or right out of the way - but not minimized

Screen savers are OK, however some applications stop updating if they are not the active window, this is developer choice and is not possible to easily change.

AppTestStudio itself can run minimized with no issues - AppTestStudio Automation is run in a separate thread that does not stop when AppTestStudio is minimized.

## Copying a project to run locally
Copy the project folder into your "Documents\App Test Studio" folder.

Typically "C:\users\(logged in user name)\Documents\App Test Studio"

Or Start-> Search for "Documents"


# Fair Use Statement
This repository is intended for educational purposes only. Examples and demonstrations may include screenshots or references to third‑party software applications. Such materials are used under the principles of fair use as defined by U.S. copyright law (17 U.S.C. § 107), specifically for:

Teaching and learning: illustrating how to use automation software to capture and process screenshots.

Research and commentary: providing technical guidance and analysis of automation workflows.

Non‑commercial use: all examples are provided solely to educate users on automation techniques.

No claim of ownership is made over any third‑party content depicted in screenshots or examples. All trademarks, logos, and software remain the property of their respective owners.

The automation software itself is released under the GNU General Public License v3 (GPL‑3.0). You are free to use, modify, and distribute the software in accordance with the terms of that license.

