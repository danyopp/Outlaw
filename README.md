Outlaw is a command line game I wrote to put together a bunch of c++ concepts mostly centered around class inheritance. The main purpose of the game is for the player to act as the town sheriff. The sheriff must gather clues and supplies by traveling to different locations around townand talking to towns people about a local outlaw who kidnapped the mayors daughter. Time is limited and the sheriff only has so many steps he can travel before he must leave to rescue the mayors daughter. To travel, the player should consult the map to see the current location, and select an option in the menu between 1 and 4 depending on the direction the user wants to move.  The player can also review all of the clues they have recieved by selecting option 7 on the menu. Certain locations also have opportunities, or in some cases distractions, that the sheriff must decided whether to indulge in. 

Once the player is out of time/visits, they will be asked to select a hideout to ride to and check for Jimmy Fasthands. The player needs to select the appropriate hideout based on the clues received or the player will lose. If the player does select the write hidout location, then he will need to be perpared to take on the outlaw with the supplies he was able to gather around town. At any one time, the Sheriff can only carry three items. If the sheriff has three items and is offered another item, the sheriff can choose to reject the offer or discard a current item and accept the offer. The sheriff can receive offers by traveling around town and associating with towns people.


The game is optimized to compile with gcc

make -			compiles game and creates outlaw.exe
make clean - 	deletes executable and object files

Author: Daniel Yopp
Date: 12/10/19