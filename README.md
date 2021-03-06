BrainGoggles
============

The BrainGoggles Project, 
Scott Little, 2013
GNU GPLv3

BrainGoggles is a project that attempts to create a low-cost NIR brain imaging device.  What are some of the things you could do with it?  How about control a mouse with your mind or be able to teach it basic shapes based on your own vision?  It's up to you!  By making this an open-source project, I hope to just get the ball rolling.  Send me a message at scott.alan.little[at]gmail.com if you are interested in getting involved.  I need real programmers to help me fill in the gaps in my hack-job style programming.  And I need enthusiastic people even if you aren't a programmer! 

Currently this consists of an Arduino (with a BrainGoggles shield) and an Android phone.  The Arduino shield consists of 4 LEDs and 16 NIR photodetectors.  I made version 1.0 of the board for testing, but as development picks up speed and I work out some of the bugs, a new version will be released and available for purchase.  Stay tuned at http://www.braingoggles.com for updates on this project.

-------------------------
BrainGoggles Log

Android 2.3, Motorola Droid 3
Ketai 8b for Gingerbread
Processing 2.0b7 (64 bit) on Windows 7 (64 bit)
Arduino 1.0.3 (64 bit), DFRobot Nano ATMega328, DF-BluetoothV3

BrainGoggles is a fork in AntiLightSwitch v.0.0.3

-----------------------------------
Update 5/24/2013 v.0.0.3
-BrainGoggles Android removed the drawing of spheres and added an oscilloscope to display the voltage on one input.

Update 8/3/2013 v.0.1
-BrainGoggles is now v.0.1 to move into Beta version so that when it works, 1.0 will match the board version.

Update 8/7/2013 v.0.2
-I will now move from v.0.1 to v.0.2 to work since v0.1 shows basic signs of working in the 1.0 board for a single input (input 2)
-The first thing I'm trying with v.0.2 is updating the IDEs and recompiling:
Android 2.3.4, Motorola Droid 3
Ketai 8 for Gingerbread (9 is for Android 2.3.7)
Processing 2.0.1 (64 bit) on Windows 7 (64 bit)
Arduino 1.0.5 (no bit specified), "Chinese" Nano 3.0 with ATMega328, DF-BluetoothV3
-At first glance, it looks like everything worked!

Update 10/22/2013 v.0.4
- I finally got the Android and Arduino communicating at the same time by putting the bluetooth on different pins and using software serial.

Update 10/22/2013 v.0.4.1
-The front LED can vary intensity based on "t" and "y" key presses.
