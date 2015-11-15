# Introduction #

OmniPage was designed and coded by Matt Howard, Phil Lopreiato, and Evan Dorsky. It is a database-oriented modular content management system that allows for simple administration and design of a web site. The OmniPage system separates code and content, making editing and maintenance easy. All code is contained within included PHP scripts and all content is stored in the database. The OmniCore takes the content from the database and integrates it with the code and skins, allowing for a separation of source code and content. This makes a very powerful and modular CMS.

# Details #
## Pages ##
Pages in this system are stored in the database. The OmniCore will find the queried page in the database, and return all of the content associated with that page.

## Modules ##
Adding and modifying content on a page is very easy to do, and does not require knowledge of HTML or PHP. To add a module, the user simply needs to click the edit button at the top of the page and select "Add Module." The user then picks which module type to add and selects it.
Modules are also very easy to edit. An administrator simply has to select "Edit Module" from the drop down box and select the module to edit. Then, a graphical method of editing the module will appear, as determined in the module PHP file. Once the edit has been made, the new information will be updated in the database.
Administrators also have the ability to review edits made to a module. They can view past states of modules and revert to that state if necessary. All edits are stored in the database along with other information related to that edit, including the user, time, IP, and previous content.
This ability to easily edit content on the site is very important. It makes it so editing and maintaining the website is no longer a role for someone who knows HTML. Now, the website content is no longer directly tied to the source file, making for an easily modifiable and modular experience.

## Skins ##
The OmniPage system is also a skinnable system. The ability to use skins makes it much easier to change the website's design. Previously, the programmers would have to completely change how the site works in the very low level files in order to change the formatting. With the OmniPage skin system, changing how the site looks is simply a matter of editing a skin file. Skin files are HTML, CSS, and Javascript files that manage how the site appears to the user. These files are passed dynamic content through the module files via special functions. This content is then displayed in the skin and shown to the end user. Now, when the website team would like to change how the site looks, they simply have to create a new skin with all the necessary files, instead of recoding the site. Skins can also be used to provide a dynamic viewing experience. A special skin can be used to simply shake things up or to make the site mobile device friendly. Either way, the ability to have skins is an important feature of the OmniPage system.

## Security ##
The OmniPage system also has native security features. All user accounts are integrated with a phpBB forums install. PhpBB has native usergroups, which the OmniCore uses to decide whether a user can see or edit a certain page. Some groups have global permissions while others can only deal with certain pages. Administrators also have the ability to give certain users or groups special permissions (that aren't native) for certain pages. This helps with maintaining website content; now any user can be responsible for a certain page and make sure it's up to date. This system also ensures security with regard to editing content.
The OmniPage system also has native log features. When an administrative action is carried out, the system will automatically append an entry to a log text file with important information regarding the edit. Username, time, and the action are recorded. This record of events helps ensure security with administrative features.

## In Use ##
OmniPage is meant to be customized and molded to the needs of any individual organization. Presently, it is installed on the websites of two non-profit organizations:

  * http://uberbots.org The UberBots
  * http://studentinit.org The Student Initiative (under construction but browsable)

Please send in the link to your OmniPage-powered website so we can add it to the list.