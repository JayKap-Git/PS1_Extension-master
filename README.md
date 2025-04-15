# PS1 Helper

![Alt text](assets/icon.png) <br/> <br/>
DISCLAIMER:

The extension is provided as it is, without any warrenty or libaility. <br/>
Although all effort has been put in to throughly test the extension, and make sure it is safe and error free, but in any case **PLEASE DOUBLE CHECK EVERYTHING.** <br/>
**MAKE SURE TO ALWAYS DOUBLE CHECK IF IMPORTS AND EXPORTS ARE CORRECT.** <br/>
**MAKE SURE TO DOUBLE CHECK THAT ALL INFO PROVIDED BY THE EXTENSION.** <br/>
**I shall not be liable in case someone messes their PS because of using this extension.** <br/>
That being said, if you found any issue, or have any suggesions, feel free to share them with me at f20212645@pilani.bits-pilani.ac.in
<br/>
<br/>

**Note:** This extension has been modified and maintained for PS1 by Jayant Kapoor (f20231099@pilani.bits-pilani.ac.in). Original extension was created for PS2 by the original author.

**About the PS1 Modifier:**
Jayant Kapoor is a BITS Pilani student who has adapted this extension for PS1 students. 
He will be maintaining the project data and ensuring the extension works smoothly for PS1 preferences.

**Modifications made for PS1:**
1. Updated the extension to work with PS1 project data structure
2. Modified the data loading mechanism to work with local JSON file
3. Updated the export functionality to save as PS1_Preference.xlsx
4. Adapted the UI to display PS1-specific project information
5. Optimized the code for better performance with PS1 data
6. Will be maintaining and updating excel.json with the latest PS1 project data
<br/>
<br/>

WHY USE THIS EXTENSION: <br/>
1) The Extension injects a new table at the top of PSMS site, which contains all the relavent information about each project of the currently selected station on PSMS site. (Stipend, Branches, Project Description, ect). <br/>
2) The injected pannel also provide new ways to add/remove items to the top or to the buttom of the already sorted list, helping in much faster. <br/>
3) The extension also allows you to save and load your preferences as an exel sheet. This way, you can share it with your friends, and also have a backup in case PSMS decides to not save your preferences, like it sometimes likes to do.
4) Undo and redo incase you mess something up!
5) The project data (excel.json) will be regularly updated to ensure you have access to the latest PS1 project information.

<br/>
<img src="https://i.imgur.com/Y8sYBaz.png" width="1024" height="416" />
<br/>

HOW TO INSTALL/ENABLE: <br/>

While we wait for the extension to get approved on the Chrome Store, the only way to use it is as follows: <br/>
1) Download ZIP of this repo from github. <br/>
2) Extract the ZIP somewhere <br/>
3) Goto chrome://extensions, and make enable Developer mode. <br/>
4) Click on 'Load unpacked' and point to the extracted folder. <br/>
5) Goto https://psms.bits-pilani.ac.in/stationpreference/selectpreference AND REFRESH THE PAGE ONCE.
6) Until the extension is uplodaded on Chrome Store, you need to remove the old extension and repeat the steps to update it.
7) To get the latest project data, make sure to update the extension regularly as excel.json will be updated with new project information.
<br/>

HOW IT WORKS: <br/>
Excel file "List of project titles and description (April 13th, 2025)" is converted to JSON and uploaded in it<br/>
<br/>