# Krypton-Toolkit-Suite-Extended-NET-4.7.1

=======

## An extension to the Krypton Toolkit suite of controls for .NET framework 4.7.1

======

## 2018-02-25 Initial commit
* Added a new toolstrip menu item UAC shield control
* Added/cleaned up documentation for methods
* New setter/getter methods for certain properties in `Global Utilities`
* New method `ElevateProcessWithAdministrativeRights(string processName)` for elevating your application with administrative rights (to be used in conjunction with the recently added UAC shield controls)
* New `CODE_OF_CONDUCT.md` file for project
* Krypton UAC shield button
* New options for developers to check if the user is running Windows 7 or higher. 64-bit checks will follow soon.
* Extended 'KryptonTextBox' to have watermark functionality.
* Wrapped 'KryptonTextBox' into a toolstrip container object to make it easier to add new functionality i.e watermarks.
* New icons for messageboxes
* New `Globals.cs` class for custom enumerations. (Needs documentation finishing off)
* NOTE FOR FUTURE REFRENCE: Find suitable icons for messageboxes (CC license maybe?)
* Fixed bug with Krypton outlook grid
* Incorporated a 'base' Krypton messagebox as a reference for extending
* Fully incorporated Krypton outlook grid code
* Krypton outlook grid 45% complete
* Altered assembly info
* Variables and comments with `color` renamed to `colour`
* Added generic C# `.gitignore` file
* Created solution with two class projects inside labeled `Extended Controls` and `Krypton Outlook Grid`
* Automatic versioning
* High DPI support configuration 