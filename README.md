### Support Jire (Charlatano)

**Donate with Bitcoin:** 3GqvcPY4rKcMxKU3jE59A2UHfV3NAyUhA6  
**Or with PayPal:** thomasgnappo@gmail.com

---

**Beginner's Guide**

This branch is being updated at [TheFuckingRat's Github Repository](https://github.com/TheFuckingRat/RatPoison)
The official branch is located at [Jire's GitHub Repository](https://github.com/Jire/Charlatano)

~~Before doing anything, make sure you have
[Java Development Kit (JDK) 13](https://www.oracle.com/technetwork/java/javase/downloads/jdk13-downloads-5672538.html)
installed. [Alternative.](https://jdk.java.net/13/) This is NOT the same thing as the regular Java Runtime (JRE), and you MUST install the JDK
in order to build Rat Poison, Charlatano, and any other Java software, and you MUST install JDK 13~~
AdoptOpenJDK is now automatically installed, and the java home variable automatically set!

The first step is to compile the source code into a usable cheat program.

* Download the latest updates (which includes the newest features) by downloading directly as a ZIP
* Extract the contents from the archive to any folder (to your desktop, for example)
* (OPTIONAL) Make sure you have Java Development Kit 13 installed, in Program Files\Java
* Double click on the "_build_" (_build.bat_) script and wait for it to complete
* If you don't have the JDK you will have the option to install it through the build.bat file

~~To set your JAVA_HOME read [here](https://javatutorial.net/set-java-home-windows-10)
Make sure to update your System Path as well, not just setting JAVA_HOME~~

Once those steps are complete, the usable cheat program can be found within the _build_
directory, and will in a directory called **RatPoison 1.5.5.1**.

From within the **RatPoison 1.5.5.1** directory, you can start the cheat by running
the _"Start RatPoison 1.5.5.1"_ script.

You can launch the cheat any time after launching CSGO.

---

**Beginner's Guide Video**

[![Beginner's Video](http://i.imgur.com/pVLW5Yr.png)](https://www.youtube.com/watch?v=PapjDtR0OMY "Charlatano")

---

Common Issues
* Overlay is black/doesn't go transparent/isn't showing up
    * The overlay only works on Windows 10, it doesn't turn transparent on W7
    * CSGO needs to be borderless/windowed for the overlay to show up on top of CS, otherwise it's just an app in your taskbar

* Game looks framey despite having normal FPS (example 144hz/144fps, but looks like 60)
    * Lowering opengl fps to 30 helps

---

Open to pull requests

Credit to Mr. Noad & 2772/Matt for a lot of help throughout this project

---

**Bug fixes only**

**ROADMAP:**
* Add bomb in fov check for last second bomb Defuse
* Door spam
* Add auto update script (from github)

---

**Recent Update**

1.5.5.1
* Removed nade helper toggle key, load the file and it will auto show with a grenade in hand, hold a decoy to see all spots

1.5.5
* Added last second bomb defuse
* Cleanup
* Null check for box esp text
* Now, the JDK automatically installs (AdoptOpenJDK), and the JAVA_HOME variable is set by the build script.


---

**Grenade Helper**
Overlay Only
Configurable in the Nade Helper Tab. Files hold all positions from when saved in the menu. The template file included is Mirage.txt, load
into a test/offline Mirage map, make sure it's selected in the drop down and then click the 'Load From File' button. Then press the key corresponding to the
'Nade Helper Toggle Key' (Default F2) to toggle visibility of the positions around the map. They are only visible when within a certain distance, to make sure you can see them
the main spots are T spawn, A ramp, and top mid, if you don't see any in these areas press the toggle key a few times to see if they do pop up, if the file is loaded
(testable in the cmd, should say 'Loading Positions'), and walk around a bit to see if you were not in range before. The 'Clear Currently Loaded' button clears all positions currently loaded. The 'Create Grenade Position'
button saves your current position, and where you are looking, and asks you to enter a name for the position (ex. 'Smoke Mid'), so go to a position, test the throw and if it's how how you want
it go back to that spot, aim appropriately and save the position (or save before and delete the position if you have to). The 'Delete At Current Position' button deletes a position if you are standing on top of it, and
is highlighted blue. The starting head position isn't completely centered on your screen, to line yourself up with the position, look straight down and center your cursor with the
middle of the circle, then look up and aim at the circle in the air.

If you have older versions of saved txt files from before Hotfix 6 these will cause an error when loaded using RP.
To fix you need to edit the text file and add the nade type (Flash, Smoke, Molly, Frag) after the position name, see the example Mirage.txt file for an example, case sensitive and must be spelled correctly

---

Base is Charlatano available [here](https://github.com/Jire/Charlatano)

---

**Available Features**
* Menu (Borderless/Fullscreen only)

* Aimbot
    * Flat Aim: Write to view angles
    * Path aim: Mouse movement
    * Group aimbot settings (Pistol/Rifle/Sniper/Shotgun/SMG)
    * Individual aimbot settings (AK/M4/etc)
    * Aim bone, speed, FOV, strictness, smoothness
    * (non-silent) Perfect aim, customize FOV and % chance to activate

* RCS
    * RCS for all weapons, customizable X & Y smoothing
    * Customizable recoil crosshair, width/length/positioning/color

* Visuals
    * Radar
    * Enemy Snaplines
    * Glow
        * Teammates, Enemies, Weapons, Grenades, Bomb, Bomb Carrier, Aimbot Target
    * clrRender chams, brightness
        * Teammates, Enemies
    * Arrow indicators
        * Teammates, Enemies, Weapons, Grenades, Bomb, Bomb Carrier
    * Box (Health, Armor, Name, Weapon)
        * Teammates, Enemies
    * Skeleton
        * Teammates, Enemies

* Bone Trigger
    * FOV, InCross
    * Customizable for each weapon category (Pistol/Rifle/Sniper/Shotgun/SMG)
    * Aimbot on activation
    * Optional trigger key
    * Initial shot delay

* Danger Zone compatible

* Misc
    * Knife bot
    * Hitsounds
    * Hitmarker
    * Bomb timer (Text Menu, Visual Bars)
    * Spectator list (Text Menu)
    * Optional sniper/scoped crosshair
    * Reduced flash
    * Bunny hop
    * Auto strafe
    * Fast stop
    * Last second bomb defusal
