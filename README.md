# Introduction to AppleScript libraries

AppleScript libraries were introduced along with AppleScriptObjective-C, in Mavericks (OSX 10.9).

The AppleScript Language Reference has this chapter on script libraries (also on p. 72 of the pdf):

https://developer.apple.com/library/mac/documentation/AppleScript/Conceptual/AppleScriptLangGuide/conceptual/ASLR_script_objects.html#//apple_ref/doc/uid/TP40000983-CH207-SW6

MacOsxAutomation explains libraries in simpler terms:

https://macosxautomation.com/mavericks/libraries/

MacScripter also has a tutorial:

http://macscripter.net/viewtopic.php?id=41638

# Listing of existing AppleScript libraries
(alphabetical order of author)

## Code by Jon Pugh

**SmartString** is a string manipulation library, "based on a 1984 Scientific American article by Niklaus Wirth about a better way to manipulate strings" (1).

http://www.seanet.com/~jonpugh/software/SmartString.applescript

(1) Quoted from Jon's mail to the AS list on December 21 2015

## Code by Lukas Reindl

Lukas has a nice collection of libraries either written by himself or copied from the net. They offer handlers for display, files & folders, iWorks, Keychain, lists, numbers, property lists, strings, Time Machine, and urls.

http://applescript.bratis-lover.net/library/

## Code by Shane Stanley

Shane is consolidating the various libraries he provides at the following link:

http://www.macosxautomation.com/applescript/apps/Script_Libs.html

At the time of writing, the link gives access to:
* **BridgePlus** (collection of handlers based on the functionality of ASObjC Runner.app, and commands that support improved bridging between AppleScript and Cocoa)
* **CalendarLib** (script library for manipulating calendar events without using Calendar.app)
* **DefaultsLib** (makes it simple to take advantage of the built-in defaults system for storing your scripts' preferences)
* **Dialog Toolkit** (script library for showing enhanced dialogs)
* **FileTagsLib** (to retrieve and set file tags)

Shane also posted three sample libraries to the AppleScript list in December 2013. "All were based on an object-oriented design shamelessly borrowed from SmartString, down to the names." (1) The code will eventually be consolidated on Shane's page, but I'm putting the links here in the meanwhile.

**Smartset** (One of the useful classes in Cocoa (and other languages) is the set, which is like a list except each item can only appear once. Sets are not normally ordered like lists, but Cocoa also has ordered lists, which maintain their order. Anyway, they are a good class to show the convenience of using ASObjC-based script libraries.)
http://lists.apple.com/archives/applescript-users/2013/Dec/msg00057.html

**SmartRecord** (This is an ASObjC-based library for a SmartRecord object. AppleScript records have several limitations: you can't get the keys/labels as strings, you can't delete items from a record, and you can't coerce them to text. Unfortunately the scripting bridge ASObjC relies on has a limitation too: it drops entries whose value is missing value. The SmartRecord will return an error if you pass it a record with a value set to missing value (or if one of the labels is an AppleScript keyword).
http://lists.apple.com/archives/applescript-users/2013/Dec/msg00113.html

**SmartList** (This is an ASObjC-based library for a SmartList object, similar to the SmartSet)
http://lists.apple.com/archives/applescript-users/2013/Dec/msg00093.html

(1) Quoted from Shane's December 22 mail to the AS list

## Code by Chris Stone

Chris' gist page is here:

https://gist.github.com/ccstone

It includes:
* **REFERENCES FOR LEARNING & USING APPLESCRIPT** lists various references to learn and become familiar with AppleScript.
* **Edit_Email_in_BBEdit.applescript** finds the selected email message with Spotlight and open it in BBEdit/TextWrangler for editing.
* **Desktop_Sweeper.applescript** creates a dated folder inside ~/Documents/Sweep Desktop/ with newly swept items.

