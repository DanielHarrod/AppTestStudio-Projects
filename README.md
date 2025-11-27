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

Copy the project folder into your "Documents\App Test Studio" folder.
Typically "C:\users\(logged in user name)\Documents\App Test Studio"
Or Start-> Search for "Documents"


