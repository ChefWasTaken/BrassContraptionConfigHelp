# BrassContraptionConfigHelp
This Repo is made to help people who don't quite understand the Brass Contraption values
---
What is a Spikey ball?: a Spikey ball is basically those balls that those Brass Contraptions throw at you (you could probably guess this)
* Prep Duration (float): This value reloads basically everything the Brass Contraption is doing (I guess?),
* Time Between Preps (float): This config name may be named wrongly but it is what it is, the time between preps or put simply, the time between each Spikey Ball that the Brass Contraption adds
* Barrage Duration (float): I don't know this one well enough buut this seems to be the time where the Brass Contraption tries to attack you
* Time Between Barrages (float): this is really simple, this is the time it takes to fire the Spikey Ball

All in all there is a bit of calculating you'll have to do to keep modifying these values, from what I've tested it seems that;
Prep Duration's value needs to be at least (Time Between Preps * 3) + 1 and Barrage Duration needs to be (Time Between Barrages * 3) + 1

if you add them as such you should have a slow working Brass Contraption or Bell Monster/Master; that still works with their own Attackspeeds, please note that if you want to reset these their default values are listed here just incase the config breaks or something

* Prep Duration : 2
* Time Between Preps : 0.2

* Barrage Duration : 3
* Time Between Barrages : 0.4

or use the command resetbcndefaults in the console and it should just set all the Base Values to default
---
if you have any further questions please Direct Message me at Discord : ChefImages#2827
