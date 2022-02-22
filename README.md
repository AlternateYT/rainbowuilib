# rainbowuilib
UI Lib made by me in 1 day, the module is currently on version 0.01

Module Version 0.02

This UI Lib was designed for me only, however I soon decided shortly after starting to develop the UI Lib, I wanted to make it public, however I do not plan to make it
open source at the moment.

This repository includes a license, if you are planning to make a copy of it, etc etc, then you'll want to read the rules of the license before doing so, or well: its
recommended.

The current license is Mozilla Public License 2.0

Report bugs to my discord user, EternitiedDeath#7983

# Built-In Functions 
lib.createWindow(<windowName - String>) Creates the window with the following name/string
  
lib.setVersion(<versionNumber - Number>) Sets the version of the window with the following version/number
  
lib.createTab(<tabName - String>) Creates a tab on the side bar, up to 8 are currently allowed
  
lib.hideWindowSideButton(<tabName - String>) Hides or closes the gui when the following tab button is pressed
  
lib.createFrame(<frameName - String>) Creates a frame (Can be paired with a tab button)
  
lib.showFrameSideButton(<tabName - String>, <frameName - String>) When the following tab button is pressed, it will show the following frame
  
lib.createFrameText(<labelText - String>, <frameName - String>) Adds text with the following text to the following frame (Can be paired with lua)
  
lib.createFrameButton(<buttonText - String>, <frameName - String>) Adds a button with the following text to the following frame (Can be paired with lua)
  
[NEW] lib.createFrameToggle(<toggleName - String>, <frameName - String>, <true/false - boolValue>) Adds a toggle with the following name to the following frame with the default bool, if true it'll be automatically set to true when you open the gui, if false it'll be automatically set to false when you open the gui. (Can be paired with lua)
  
lib.createFrameSlider(<sliderName, - String>, <minValue - Number>, <maxValue - Number>, <frameName - String>) Creates a slider with the following slider name, min value for the slider, max value for the slider, and puts it in the following frame (Can be paired with lua)
  
lib.notificationOnHide = <true/false - boolValue> If set to true, it'll show a notification when the window is closed or hidden by a exit/hide function that allows you to re-open the gui when closed. If set to false, it won't show a notification when the window is closed or hidden by a exit/hide function.
