### Version 2.2 (2021/12/12)
* Added compatibility with v9. This was a breaking change, so use 2.1 for 0.8.x and earlier.
* Fixed CustomHotbar app being added to UI twice
* Note: support for v9 keybinding library coming soon.

## Version 2.1.0 (2021/05/20)
0.8.x update, a few new features, and misc bugfixes
* Updates Custom Hotbar for Foundry 0.8.x release branch while maintaining backwards compatibility.
* NEW FEATURE: Ability for users to disable their own custom hotbar entirely if they don't want it (and core hotbar too, because why not?)
* NEW FEATURE: keybinding library for a high level of keybinding customization and reliability improvements.
* Adds color settings library as an official dependency to assist with hotbar customization
* Portuguese translation (sorry about the delay rinnocenti!!)
* Changed hotbar coloration to match core foundry (#0000FF60 is the "classic blue" if you want to change back)
* Firefox compatibility improvements
* Module is now less talkative in console log
* Many miscellaneous bugfixes (see changelog).

## Version 2.0.6 (2020/10/21)
* Marked as compatibile with 0.7.5 after successful testing.
* The weird duplicate custom hotbar issue mysteriously fixed itself in 0.7.5
* Fixed Shift-number keybind (thanks Nihilistkitten and everyone else for the investigation)
* Updated ColorSettings Library by moving to the stub solution.

## Version 2.0.5 (2020/07/27)
Fixed Z index issue introduced in v2.0.3 that was preventing the right-click context menu of the core Foundry hotbar from being on top of the Custom Hotbar. My attempted fix for the same issue in 2.0.4 was not actually present in the release due to versioning issues. Oops.

## Version 2.0.3 (2020/07/24)

Updated built-in color settings library
Added suppport for dropping Roll Tables on the Custom Hotbar (such as with The Furnace module)
Script reorganization and cleanup that hopefully didn't break anything
Minor CSS improvements
* Fixed z-index of custom hotbar to match hotbar (70) and improved macro tooltip z-indexing
* Improved display of color pickers in settings
* Fixed bug where Custom Hotbar settings styles were accidentally applying to other module's settings

## Version 2.0.2 (2020/07/21)

Fixed firefox compatibility (again)
Updated built-in color settings library

# Version 2.0 (2020/07/19)

Added settings to control Custom Hotbar position and color
Added settings to provide the same control to the Core Hotbar
Added settings for both global defaults and individual user settings
Added new keybinding (Ctrl-Shift-1 through 5) to change core Foundry Hotbar page number
Fixed compatibility with Firefox
Added localization strings for the new settings

# INITIAL RELEASE v1.5 (2020/07/05)

Added ability to automatically handle dragging from character sheet onto custom hotbar, including full MQoL and BetterRolls support.
Added support for all reamining dragging and dropping scenarios, including between Core and Custom Hotbars.
Added keybinding for CHB: Shift + slot number (just like a regular macro keybinding, but with Shift added).
General improvements/bugfixes

## EARLY BETA v0.0.5 (2020/06/14) Basic macro hotbar functionality 
Added writing established (writing to and reading from User.Data.Flags). Also handles the most important events to allow basic custom hotbar funtionality to be performed.

## v.0.0.1 Initial version 
First attempt to display the hotbar in any fashion.

