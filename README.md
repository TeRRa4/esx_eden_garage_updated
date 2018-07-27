# esx_eden_garage
## ENGLISH

Forked from manups4e's version, updated to match latest db structure, but also translated into English by me, an Englishman.

##


Private garage based on ESX

Single requirement:
esx_vehicleshop

The garage will only consider vehicles bought from the dealership (i.e. in the owned_vehicles table). During a reboot, all vehicle states are reset and returned to the garage.

1) You must import the .sql provided.
2) Add 'start esx_eden_garage_updated' to your server.cfg
3) The config file can be used to specify different things, including garage locations.

How to use (in-game):
Drive your car into the red circle and press 'E' to store it.
Walk into the green circle and press 'E' to see the list of your stored vehicles and recall one. 
If your vehicle is impounded, you'll have to go to one of the three impound lots and pay a fee to get it back.
