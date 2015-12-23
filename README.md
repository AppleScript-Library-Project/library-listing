# Listing of existing AppleScript libraries
(alphabetical order of author)

## Code by Jon Pugh

**SmartString** is a string manipulation library, "based on a 1984 Scientific American article by Niklaus Wirth about a better way to manipulate strings" (1).

http://www.seanet.com/~jonpugh/software/SmartString.applescript

(1) Quoted from Jon's mail to the AS list on December 21 2015

## Code by Shane Stanley

Shane is consolidating the various libraries he provides at the following link:

http://www.macosxautomation.com/applescript/apps/Script_Libs.html

At the time of writing, the link gives access to:
* **BridgePlus** v1.3.1 (collection of handlers based on the functionality of ASObjC Runner.app, and commands that support improved bridging between AppleScript and Cocoa)
* **CalendarLib** v1.0.0 (script library for manipulating calendar events without using Calendar.app)
* **DefaultsLib** v1.0.0 (makes it simple to take advantage of the built-in defaults system for storing your scripts' preferences)
* **Dialog Toolkit** v1.0.2 (script library for showing enhanced dialogs)

Shane also posted three sample libraries to the AppleScript list in December 2013. "All were based on an object-oriented design shamelessly borrowed from SmartString, down to the names." (2) The code will eventually be consolidated on Shane's page, but I'm putting the links here in the meanwhile.

**Smartset** (One of the useful classes in Cocoa (and other languages) is the set, which is like a list except each item can only appear once. Sets are not normally ordered like lists, but Cocoa also has ordered lists, which maintain their order. Anyway, they are a good class to show the convenience of using ASObjC-based script libraries.)
http://lists.apple.com/archives/applescript-users/2013/Dec/msg00057.html

**SmartRecord** (This is an ASObjC-based library for a SmartRecord object. AppleScript records have several limitations: you can't get the keys/labels as strings, you can't delete items from a record, and you can't coerce them to text. Unfortunately the scripting bridge ASObjC relies on has a limitation too: it drops entries whose value is missing value. The SmartRecord will return an error if you pass it a record with a value set to missing value (or if one of the labels is an AppleScript keyword).
http://lists.apple.com/archives/applescript-users/2013/Dec/msg00113.html

**SmartList** (This is an ASObjC-based library for a SmartList object, similar to the SmartSet)
http://lists.apple.com/archives/applescript-users/2013/Dec/msg00093.html

(2) Quoted from his December 22 mail to the AS list

## Code by Chris Stone

Chris' gist page is here:

https://gist.github.com/ccstone

It includes:
* **REFERENCES FOR LEARNING & USING APPLESCRIPT**
* **Edit_Email_in_BBEdit.applescript**
* **Desktop_Sweeper.applescript**
as well as other non AppleScript related information:
* BBEdit-TextWrangler_RegEx_Cheat_Sheet.txt

