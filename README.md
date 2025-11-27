# AppTestStudio Projects

Projects created with [AppTestStudio](https://github.com/DanielHarrod/AppTestStudio).  
You can run these projects directly or use them as inspiration for your own automation workflows.

---

## System Setup

### Monitor Settings
AppTestStudio requires the monitor resolution to match the resolution used when the project was created.  
**Important:** Monitor scaling is not supported. Set scaling to **100%**.

**Recommended steps:**
- Windows → System → Display  
- Select the monitor where the target app will run  
- Scale & Layout → Scale → **100%**

---

### Power Settings
AppTestStudio runs scripts continuously or on a schedule. It captures periodic screenshots, which requires the monitor to remain active. If the monitor sleeps, Windows stops updating the screen.

**Recommended steps:**
- Windows → System → Power  
- Plugged in → Turn screen off after → **Never**  
- Plugged in → Sleep after → **Never**  
- Plugged in → Hibernate after → **Never**

---

### Target Application Visibility
Windows optimizes graphics by not updating minimized applications. This can interfere with screenshot capture.

**Recommendations:**
- Keep the target application visible but move it off-screen (e.g., drag to the side or bottom).  
- Avoid minimizing the target application, minimized appliations do not have graphics rendered resulting in a black screen.  
- Screen savers are acceptable, but note: some applications only update when active.  
- AppTestStudio itself can run minimized without issues — automation runs in a separate uninterruped thread.

---

## Running Projects Locally
To run a project on your machine:

1. Copy the project folder into your `Documents\App Test Studio` directory.  
   Example:  
2. Or open Start → Search for **Documents** and place the project folder in the **App Test Studio** folder.

---

## Fair Use Statement
This repository is intended for **educational purposes only**. Examples may include screenshots or references to third‑party software applications. These materials are used under the principles of *fair use* (17 U.S.C. § 107):

- **Teaching & Learning:** Demonstrating automation techniques for capturing and processing screenshots.  
- **Research & Commentary:** Providing technical guidance and workflow analysis.  
- **Non‑Commercial Use:** All examples are solely for educational purposes.

No ownership is claimed over third‑party content. All trademarks, logos, and software remain the property of their respective owners.

---

## License
[AppTestStudio](https://github.com/DanielHarrod/AppTestStudio) and [AppTestStudio-Projects](https://github.com/DanielHarrod/AppTestStudio-Projects) are released under the **GNU General Public License v3 (GPL‑3.0)**.  
You are free to use, modify, and distribute the software in accordance with the terms of this license.
