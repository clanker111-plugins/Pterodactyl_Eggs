# Pterodactyl_Eggs
My recreation and edits to some public pterodactyl eggs to work on larger networks. Will add some custom eggs eventually as well!

Ark:
One of the key things left out of the base ark egg is that ark uses multiple ports to function beyond the base game port. So I had to go ahead and add a Query port variable. An example is shown below. The mininal ports required to be assigned to your server is 3, the game port, Raw UDP port and the Query port. Your primary allocated port will be the game port and you will define the Query port in the given varible location.

Server instance	       Game port	Raw UDP port	Query port	RCON port
Server game instance 1	  7777	    7778	         27015	   27020
Server game instance 2	  7779	    7780	         27016	   27021
Server game instance 3	  7781	    7782	         27017	   27022
Server game instance 4    9999	    10000	         37015	   37016
completely different ports	
*Notes*

Query Port cannot be between 27020 and 27050 due to Steam using those ports.
