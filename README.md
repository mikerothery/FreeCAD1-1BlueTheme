# FreeCAD1-1BlueTheme
## A Blue Theme for FreeCAD Version 1.1

## Background
By default, FreeCAD ships with three themes.\
FreeCAD Light - a bacic light theme.\
FreeCAD Dark - a basic dark theme.\
and FreeCAD Classic which uses the Local Operating System Fonts and Colours.\
Settings for the internal UI inside FreeCAD can be modified by the user but custom changes to menus and layouts are more complex thus requiring a dedicated system theme.

## Reason for this Theme
I'm not a great fan of dark themes so I was using the FreeCAD Classic Theme which has the look and feel of my operating system.\
Ever since the early days of Windows 95/98 and XP etc, blue has been a dominant colour so I decided to make my own FreeCAD Theme using the look and feel of a classic operating system but with a modern twist.\
The result is FreeCAD1-1BlueTheme.\
It should work under all Operating Systems.  I use Linux - hence the Tux Icon when installed via the Addon Manager.\
This is FreeCAD1-1BlueTheme, I hope you like it.

![FreeCAD1-1BlueTheme Screenshot1](https://raw.githubusercontent.com/mikerothery/FreeCAD1-1BlueTheme/main/FreeCAD1-1ScreenshotModel.png)

## Colours
FreeCAD's Light and Dark Themes incorporate appropriate UI colours that best fit the dark and light background colours.\
Whilst designing FreeCAD1-1BlueTheme, it was clear that the default UI colours for the Sketcher wouldn't work with my selected blue background.\
So I have changed the Sketcher Colours as follows:-

Unconstrained Geometry is White\
Constrained Geometry is Dull Green\
Construction Unconstrained Geometry is Light Blue\
Construction Constrained Geometry is Lighter Blue\
External Geometry is Yellow\
Fully Constrained Sketch is Bright Green\
Invalid Sketch is Red\
Constraint Symbols are Brown\
Dimensional Constraints are Dark Blue\
Referenced Constraints are Orange\
Expression Dependant Constraints are Dark Grey\
New Elements are Grey

In my opinion, the above colours provide clean easy to read sketches but can be altered in the usual way using Edit Preferences - Sketcher - Appearance.

This is an example of a simple Sketch using FreeCAD1-1BlueTheme.

![FreeCAD1-1BlueTheme Screenshot1](https://raw.githubusercontent.com/mikerothery/FreeCAD1-1BlueTheme/main/FreeCAD1-1ScreenshotSketch.png)

## How to find FreeCAD1-1BlueTheme
Run FreeCAD\
Edit Preferences - Addon Manager - Add Custom Repository (+ sign) and enter the following\
Repository URL - https://github.com/mikerothery/FreeCAD1-1BlueTheme  \
Branch - main  \
Apply - OK\
Tools - Addon Manager\
Refresh Local Cache\
Set the Filter to Any and Search for FreeCAD1-1BlueTheme\
You will find FreeCAD1-1BlueTheme in the searched list.

If you have found FreeCAD1-1BlueTheme using the Addon Manager, you will already have entered the above steps.

## How to Install FreeCAD1-1BlueTheme
Run FreeCAD\
Tools - Addon Manager\
For Filter, Select - Preference Pack\
Refresh Local Cache\
You will find FreeCAD1-1BlueTheme in the searched list\
Select it\
Install it

## Upgrading FreeCAD
On running the new version of FreeCAD for the first time, a dialog will appear offering a suggestion to copy the settings from an old version of FreeCAD\
Click - Copy Configuration (Recommended)\
FreeCAD will now copy over all the settings from the old Version.

## How to Acvivate FreeCAD1-1BlueTheme
Run FreeCAD\
Edit Preferences - General\
Change Theme to FreeCAD1-1BlueTheme\
Apply - OK\
Edit Preferences - Display - UI\
Set Style sheet (advanced) to FreeCAD1-1BlueTheme\
Enjoy.

## Screen Resolution
FreeCAD worls well "out of the box" on 1920 x 1080 screen resolutions.\
However, the Marker Size (the size of the Vertex etc. in the Sketcher) can be made more prominent by changing:-\
Edit Preferences - Display - 3D View - Marker Size\
Set to 9px for a 1920 x 1080 (Standard 1K) display\
Set to 13px for a 2160 x 1440 (Surface Pro) display 

## Add the New Settings for FreeCAD 1.1 that weren't in FreeCAD 1.0
Padding etc\
Edit Preferences - Part Design - General - Preview\
Check - Show final result by default when editing features\
Uncheck - Show transparent preview overlay by default when editing features\
Check - Highlight the profile used to create features

Origins etc\
Edit Preferences - Display - 3D View - Rendering\
Set Datum Size to 300%

New Pad Technique\
Edit Preferences - Sketcher - General\
Check - Generate Internal Faces

External Geometry\
Edit Preferences - Sketcher - General\
Check - Always add external geometry as construction

Size of Recent File List\
Edit Preferences - General - General\
Size of Recent File List - I set this to 16

Vertex and Line Sizes\
Edit Preferences - Part/PartDesign - Shape Appearance\
Line Width to 1px\
Vertex Size to 1px

## Contact
If you have any comments, please email me on mike@maidencombe.com

All the best  \
Mike

