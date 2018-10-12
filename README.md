# OmniFocus 3 AppleScripts

## About

This repository contains useful scripts for OmniFocus 3. I have also included a
directory with some icons created from the FontAwesome set. I am planning to
update this repository somewhat regularly as I write new scripts I find useful.
Some scripts take inspiration and may be similar to the popular collection by
[Brandon Pittman](https://github.com/brandonpittman/OmniFocus).

## Installation

For any of the scripts to work you have to first install the library script
that can be found [here](https://github.com/Rahlir/OmniFocusScripts/tree/master/Library).
Compile the file **omnifocuslib.applescript**.Then, copy the compiled file
**omnifocuslib.scpt** to the directory `~/Library/Script Libraries/`. The
Terminal commands to do that are 

```bash
osacompile -o Library/omnifocuslib.scpt Library/omnifocuslib.applescript
cp Library/omnifocuslib.scpt ~/Library/Script\ Libraries/
```

To install some OmniFocus script, the process is similar: Compile the script
using `osacompile` and then copy it to the OmniFocus 3 script directory. To see
what your script directory is, open OmniFocus 3 and navigate to `Menubar ->
Help -> Open Scripts Folder`. Typically, this directory is either

```
~/Library/Application Scripts/com.omnigroup.OmniFocus3
``` 

or

```
~/Library/Application Scripts/com.omnigroup.OmniFocus3.MacAppStore
``` 

depending on how you purchased OmniFocus. If there are additional installation steps for
a particular script, these will be outlined in a README.md in the script's
folder.

## Scripts

1. **[Sort Tags](https://github.com/Rahlir/OmniFocusScripts/tree/master/Sort%20Tags)**: 
Define categories of tags and their priorities. Then, you can use the script to
order your tags according to the priority of the category.
2. **[Defer](https://github.com/Rahlir/OmniFocusScripts/tree/master/Defer)**:
Defer all the selected tasks to tomorrow. This script can easily be modified to
defer all the selected tasks to _x_ days from today. Makes deferring much
quicker and can be done in batch.
3. **[Edit Links](https://github.com/Rahlir/OmniFocusScripts/tree/master/Edit%20Links)**:
Edit displayed name of all links in notes of all selected tasks or projects.
Useful if you often add links to your notes and do not want to manually edit
their displayed name one by one.

## Icons

To use the Scripts in OmniFocus, one typically adds a button for that script in
the toolbar. OmniFocus uses the script's Finder icon for the script button. If
you are using more than 1 script it can be difficult to distinquish them.
Moreover, the default icon, in my opinion, looks boring. Hence, I have
converted some FontAwesome icon to the macOS `.icns` format. The icons can be
found in different colors using mostly the OmniFocus 3 dark color pallette. To
use them, open the location of a script in Finder and open the _Get Info_
window. Then, drag the `.icns` file to the script's icon in _Info_ window.

You can see my OmniFocus toolbar with those icons used here:
![toolbar](https://Rahlir.github.io/Assets/toolbar.png)

The icon files can be found [here](https://github.com/Rahlir/OmniFocusScripts/tree/master/Icons).

### Attribution

The icons are modified icons from the FontAwesome collection. The official
website can be found [here](https://fontawesome.com/). There is also a [Github
repository](https://github.com/FortAwesome/Font-Awesome).

