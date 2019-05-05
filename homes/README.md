![Banner](https://raw.githubusercontent.com/Plagiatus/datapacks/master/homes/banner.png "Homes Banner")

# Homes

[latest version (v1.1)](https://github.com/Plagiatus/datapacks/raw/master/home/homes_v1.1.zip) (1.14)

## What it does

Homes allow you to save positions in the world and teleport to them whenever you want, including different dimensions.

This Datapack allows you to set unlimited homes in any world. The players of the world don't need OP to use the commands.

## How to set up

Download the zip file and place it into your `world/datapacks` folder. If the world is already running, run `reload`. That's all you need to do.  

You can look at the ingame-help for the datapack by running

    /trigger home.help

But while you're here you might as well read the long explanation below ↓

## Commands explanations

### General

- All commands need to be prefaced with `/trigger`.  
- Some of the commands allow you to specify a specific home (the ones annotated with "(set #)"). You will always have to identify the home by its ID and cannot identify it via its name.  
- If you're not specifying a specific home in a command that allows for it, it will default to home number 1.  
- Negative values are ignored.  
- _There are no undos._

### Specific commands

`/trigger home.help`  
Display the ingame help page.

`/trigger home (set #)`  
Teleport to one of your homes. Defaults to Home #1 if nothing else is specified.

`/trigger home.set (set #)`  
Set a new home location. This command will also override a home if set to an existing number.

`/trigger home.delete (set #)`  
Deletes the specified home.  

`/trigger home.list`  
Lists all your homes in a list with their ids, coordinates and names.

`/trigger home.set_name (set #)`  
Sets the name of the specified home to the name of the item in your hand. **The item needs to be renamed in an anvil for it to work.** If it isn't or your hand is empty, it will not change the name.

## Further Information

**If you want to move your spawnchunks, you'll have to run this command afterwards to keep the datapack working:**

    teleport @e[type=area_effect_cloud,tag=pla_home] x y z  
	
replace `x y z` with your new worldspawn coordinates.

Homes are running out ~3 years (real time) after you've created them. If this is a concern for you, reach out to me and I'll let you know how to extend it by another 3 years.

### Contact

If you have any questions, concerns, praise or found a bug, you can contact me directly at [contact@plagiatus.net](mailto:contact@plagiatus.net) or use my [contact form](http://plagiatus.net/#contact).


### Changelog

#### 1.1
5.4.2019 Multidimensional Support

#### 1.0
4.5.2019 released