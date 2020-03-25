# Prometheus-Data-Module
### WARNING: THIS IS VERY NEW AND MAY HAVE BUGS! Open a issue if you find one.

## The future of Roblox datastores
A simple yet powerful Roblox datastore manager with many easily customizable settings and features, such as not saving in studio (you can turn it on and off in the settings), automatic data table managment that will manage making a table out of the player's data, getting the table when needed, and saving the table when the player leaves, without you having to get your hands metaphorically dirty.
## Features
#### Easy data retrieval and saving
PDM can automatically retrieve and save data while maintaining efficiency, so you can spend more time on the fun part of making your game.
#### Like traditional Leaderstats datastores, except WAY better
Using PDM is even easier than Leaderstats-type datastores, while being more powerful and efficient too.
#### Designed for beginners
Instead of whacking your head while staring at the official Roblox data module (Link to the official one: https://developer.roblox.com/en-us/articles/Saving-Player-Data) move ahead with your game using PDM.
#### Full of potential and customization
With more than 8 (and more to come) different functions and settings to customize how you use your data, you can customize the module to your hearts content just by changing some of the settings. (Disclamer: There is a chance that you can't customize it enough, and if you can't, open an issue here.)
#### Both support for player data saving and game data saving
You can both use the player object or a name as input for a PDM function. (Currently, if your game runs multiple servers at once, there isn't a cross server messageing system in place yet, you will have to make one yourself.
## Other Stuff
#### Current Major Known Bug
For some reason when the player leaves it should automatically clear and save their data, but it yield infinitly at the SetAsync command in the Update function. If you have a solution please make a pull request.
#### Feedback needed!
If you have a bug/enhancment that needs to be fixed or have a potential solution to the player saving when leaving problem, open an issue or use a pull request.
