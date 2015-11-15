# Introduction #

For a list of functions defined in include files, go to Function Documentation
Include files are in the /includes directory. They contain many functions used in almost every part of the OmniPage system. The main include files is common.php; it will include all other necessary files. Files in the includes directory usually declare functions for use elsewhere.

# Details #

  * **common.php** - Common.php is the include file that will include all other commonly used include files. It will include all other files in this directory.
  * **mysql.php** - This file declares functions for connecting and disconnecting from the SQL database.
  * **module.php** - This file provides support for the usage of modules. It will include all module source files and declare functions useful in working with modules.
  * **skinParser.php** - This file declares the skin parser function, which gives a module the ability to provide dynamic content to a HTML file.
  * **page.php** - This file provides support for dynamic pages. It provides the infrastructure for creating and rendering pages.
  * **menu.php** - This file declares the function used to draw the menu seen on every page's header.
  * **modHistory.php** - This file provides support for module history and edit logging. It declares functions used to track edits and view/restore them.
  * **phpBBsession.php** - This file integrates phpBB (forums) sessions with the OmniCore. It provides a more versatile permission system.