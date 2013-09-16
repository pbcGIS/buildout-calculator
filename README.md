buildout-calculator
===================

A plugin for Trimble SketchUp tabulates development and parking capacity for sites and districts. This plugin is under development by PbcGIS and is offered for free, with absolutely no warranty, under the Creative Commons 3.0 Share Alike Unported License (see below).  For more information, visit www.pbcGIS.com/buildout_calculator .

To Install:
1. Find your Sketchup Installation folder:
 On Windows 7 64bit the default location for SketchUp 8's plugin folder is:
    C:\Program Files (x86)\Google\Google SketchUp 8\Plugins
OSX users will find the plugins folder under:
    /Library/Application Support/Google SketchUp 8/SketchUp/Plugins

2. Copy the entire folder "Tabulator Materials" to your sketchup materials folder within the sketchup installation folder.  Once you restart sketchup, you will have a new category in your materials window thathas these materials required to use the plugin.
 
3. Copy the plugin file "pbcGIS_buildout_calculator.rb" to the plugins folder within your sketchup installation folder.  When sketchup is restarted, you should now see a "Massing Tabulator" submenu when you right-click on things.

To Use:
1. Expose the Dynamic Components toolbar.  Choose "View > Toolbars > Dynamic Components."
2. A Site group is a two dimensional area that may be divided into parking and non-parking areas.  Areas designated for parking are colored with the "parking" texture.  Select all of the faces that are part of your site, and choose "Make Site Group" from the Massing Calculator sub-menu.
3. A Building group ordinarily an extruded shape with the roof colored with one of the roof textures provided in the Massing Calculator Materials group.  Triple-click the building object to select all of its faces, then right-click and choose "Make Building Group" from the Massing Calculator sub-menu..  

Click the group with the Component Options tool.  Choose the primary use of the building from the Use pull-down.  This use needs to correspond with the use implied by the roof texture you used.

Fill in the number of stories that are assigned to various uses within the building.  It is OK to list fractional floors.

4. A Scheme Group is a combination of any number of building groups with one site group.  To make a scheme, select your building groups and your site group, right-click and choose "Make Scheme Group."  Enter a new scheme name and if you want, you may modify the values for parking requirements for commercial and residential floor area, and the area required for each parking place.

5. To summarize the GFA and the parking balance for any number of schemes, select the schemes then right-click and choose "Tabulate Schemes".   This table may be saved as an html document and opened cut and pasted in Microsoft Excel.

License:  Creative Commons 3.0 Attribution Share-Alike Unported

You are free:
to Share — to copy, distribute and transmit the work
to Remix — to adapt the work
to make commercial use of the work

Under the following conditions:
Attribution — You must attribute the work in the manner specified by the author or licensor (but not in any way that suggests that they endorse you or your use of the work).
Share Alike — If you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.
With the understanding that:

Waiver — Any of the above conditions can be waived if you get permission from the copyright holder.
Public Domain — Where the work or any of its elements is in the public domain under applicable law, that status is in no way affected by the license.
Other Rights — In no way are any of the following rights affected by the license:
Your fair dealing or fair use rights, or other applicable copyright exceptions and limitations;
The author's moral rights;
Rights other persons may have either in the work itself or in how the work is used, such as publicity or privacy rights.
Notice — For any reuse or distribution, you must make clear to others the license terms of this work. The best way to do this is with a link to this web page. 

