# D3DynamicTreeLayout-QS
Qlik Sense extension that displays an Hierarchical Tree using D3, with user interaction.

Tested with Qlik Sense June 2019 Patch 3.

Features included are:
  * Expanded distance between node levels for use with fewer levels
  * Offset distance from edge to handle longer node names
  * added persistent tooltip on the righthand edge for use with horizontal lr orientation
  * moved node name location on vertical layouts to be on the opposite side of the links

An example and tutorial app can be found in the 'App Example and Tutorial' folder.

### Release History (most recent first)
 * v1.4.1 - New features from master branch
 * v1.4 - New feature! Fully customize look of Rectangle boxes with HTML
 * v1.3.1 Corrected 2 major bugs:
 		- Configuration of extension from scratch would pass on verification of Node Name specification in latest Qlik Sense releases;
 		- Selection of a node that would be on last depth level would not respond and select on application
 * v1.3 - Added Calculation Condition
 * v1.2.4 - Fixed an issue that would prevent the rendering of the extension in Qlik Sense v3.2.3
 * v1.2.3 - Fixed an issue that prevented the creation of the extension from scratch on v3.2
 * v1.2.2 - Fixed an issue that would restrain the rendering in Qlik Sense v3.2
 * v1.2.1 - Added a new verifications before loading the tree.
 * v1.2 - Added 2 new orientations for the tree - right to left and bottom up
 * v1.1.1 - Minor update - added some verifications before loading the tree. If something wrong is detected it
   displays a warning in the extension's placeholder and avoids loading the tree.
 * v1.1 - Added independent coloring for nodes and links
 * v1 - Initial relase of the extension


![alt text](./Screenshots%20Example/Screenshot-1.PNG?raw=true) 
![alt text](./Screenshots%20Example/Screenshot-3.png?raw=true) 
![alt text](./Screenshots%20Example/Screenshot-4.png?raw=true) 
![alt text](./Screenshots%20Example/Screenshot-5.png?raw=true) 
![alt text](./Screenshots%20Example/Screenshot-8.PNG?raw=true) 
![alt text](./Screenshots%20Example/Screenshot-7.PNG?raw=true)
