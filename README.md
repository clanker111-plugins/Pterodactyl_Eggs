# Pterodactyl_Eggs
My recreation and edits to some public pterodactyl eggs to work on larger networks. Will add some custom eggs eventually as well!

Ark:
------

One of the key things left out of the base ark egg is that ark uses multiple ports to function beyond the base game port. So I had to go ahead and add a Query port variable. An example is shown below. The mininal ports required to be assigned to your server is 3. 

The game port, Raw UDP port and the Query port. 

Your primary allocated port will be the game port and you will define the Query port in the given varible location.

[![imgur](https://i.imgur.com/jbvbrpZ.png)](#features)


*Notes*

Query Port cannot be between 27020 and 27050 due to Steam using those ports.
