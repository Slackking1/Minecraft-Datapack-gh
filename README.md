# Minecraft concept datapack for functions generated whit rhino grasshopper. 

Place repository in the world save folder under datapacks. eg. World->datapacks->THIS repository.

The datapack is currently runnning version 1.20.1

## Design of grasshopper scripts for minecraft. 
-Create you design as normal
-in general make a insert block in point 0,0,0 this works as a reference for relative coordinates.
-Chop it into peace, make a concat function so each coordinate is a minecraft command eg. 
  setblock ~30 ~25 ~1 stone
  setblock ~31 ~25 ~1 stone
  setblock ~32 ~25 ~1 stone
  setblock ~33 ~25 ~1 stone
  setblock ~33 ~26 ~1 stone
  setblock ~34 ~26 ~1 stone
  setblock ~34 ~27 ~1 stone
  setblock ~35 ~27 ~1 stone
  *only one command for each line in the .mcfunction file
- Minecraft functions can maximum place about 65.000 block in one function, is you build larger make multiple functions,
and use the 0,0,0 block as reference for inserting.
- results from grasshopper is stored in a .mcfunction file -> edit in for instance cisual studio code. Can be pushed directly from grasshopper,
stream the results from the panel into the file.

To view the grasshopper side of things have a look at my other repository with a sample definition in it. 
-> https://github.com/Slackking1/GH_Scripts
