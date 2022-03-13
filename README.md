# rainbowuilib
UI Lib made by me in 1 day, the module is currently on version 0.02

Module Version 0.04

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
  
lib.createFrame(<frameName - String>) Creates a frame
  
lib.showFrameSideButton(<tabName - String>, <frameName - String>) When the following tab button is pressed, it will show the following frame
  
lib.createFrameText(<labelText - String>, <frameName - String>) Adds text with the following text to the following frame
  
lib.createFrameButton(<buttonText - String>, <frameName - String>) Adds a button with the following text to the following frame
  
lib.createFrameToggle(<toggleName - String>, <frameName - String>, <true/false - boolValue>) Adds a toggle with the following name to the following frame with the default bool, if true it'll be automatically set to true when you open the gui, if false it'll be automatically set to false when you open the gui
  
lib.returnButton(<buttonName - String>) Returns a side button with the following name

lib.returnFrame(<frameName - String>) Returns a frame with the following name
  
lib.hideWindow() Hides the current window

lib.showWindow() Shows the current window
  
[NEW] lib.toggleWindow() Toggles the current window depending on if its being shown or if its being hidden
  
[NEW] lib.createFrameKeybind(<keybindName - String>, <frameName - String>, <startingKeybind - String>) Adds a keybind with the following name to the following frame with the following starting keybind already preset
  
[NEW] lib.returnFrameKeybindValue(<keybindName - String>, <frameName - String>) Returns the current value of the following keybind in the following frame
  
[NEW] lib.returnFrameObject(<objectName - String>, <frameName - String>) Returns a frame object in the following frame with the following name
  
[NEW] lib.setHideGUIKeybind(<keybind - String>) Sets the keybind required to hide the gui with the following keybind
  
lib.createFrameSlider(<sliderName, - String>, <minValue - Number>, <maxValue - Number>, <frameName - String>) Creates a slider with the following slider name, min value for the slider, max value for the slider, and puts it in the following frame
  
lib.notificationOnHide = <true/false - boolValue> If set to true, it'll show a notification when the window is closed or hidden by a exit/hide function that allows you to re-open the gui when closed. If set to false, it won't show a notification when the window is closed or hidden by a exit/hide function.
