# Introduction #

The OmniCore system is built around skins. A skin is stored in the /skins directory and is in a directory with the skin name. Within that directory are three other directories: 'css', 'images', and 'scripts' To make a skin, there are certain skin files needed.

# Ghost Skins #
It's possible for skins to be 'ghosted' off of other skins, that is, you don't need to define every skin file for every skin. If a skin is missing a certain file, then it will request that file from the parent skin.

# Required Skin Files #
## Skin Directory ##
  * basic\_module.html
  * calAddForm.html `*`
  * calBlankDay.html `*`
  * calDay.html `*`
  * calEdit.html `*`
  * calendar.html `*`
  * calEvent.html `*`
  * calWeekHeader.html `*`
  * calFullHeader.html `*`
  * controlPanel.html
  * forumsActivity.html `*``*`
  * forumsActivityLine.html `*``*`
  * main.html
  * mentorList.html `*`
  * mentors.html `*`
  * module\_list.html
  * module\_list\_line.html
  * newsEdit.html `*``*``*`
  * newsHome.html `*``*``*`
  * second\_menu\_item.html
  * simpleScriptEdit.html `*``*``*``*`
  * simpleScriptEditVars.html `*``*``*``*`
  * top\_menu\_item.html
  * videos.html `*``*``*``*``*`
  * videoThumb.html `*``*``*``*``*`
Skin files with `*`(s) are dependent on a module (in other words, they are only needed if their module is being used.
  * `*` - calendar module
  * `*``*` - forums activity module
  * `*``*``*` - news feed module
  * `*``*``*``*` - script module
  * `*``*``*``*``*` - video module

## CSS subdirectory ##
  * **cal.css** - This file contains all CSS for the calendar. For definitions, please see the current skin file
  * **main.css** - This file contains all main CSS for the site. For what to add, see the current file Additionally, jQuery CSS is in this directory, but may be omitted if jQuery isn't used.

# Skin Functions #
  * skinParser();