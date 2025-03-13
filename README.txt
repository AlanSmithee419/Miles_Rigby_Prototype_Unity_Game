IMPORTANT: As the game is provided as an executable without source code, I understand there may be security concerns. For those reviewing this for job applications, I'm 
happy to provide alternative demonstrations of this work, such as screenshots or video/live demos. Please reach out to me if you'd like to pursue these options.

This project is a prototype version of a simple UI-based incremental game built in Unity using C# that can be run through Incremental.exe.
The game is currently being refactored elsewhere to allow easier expansion of mechanics in the future, better following object oriented and project design principles.
Game code is contained in a seperate, private repo.

The game uses the setting of a survival game with fantasy elements.
There are three basic types of resources:
  Raw resources, collected with no cost (left of the game screen)
  Intermediate components which cost raw resources (middle)
  Final constructions which can cost any combination of other types of resources and have an impact on gameplay in some way (right)

The player can switch between resources by clicking each resource's associated button, and can only have one active task at a time.
The player is given information on the costs and bonuses of different items where relevant (displayed on tool tips when hovering over a resource's button),
as well as how much of each resource they have and how close they are to completing a task (indicated by a progress bar).

Different resources take different amounts of time to produce, and production of a resource also levels up skills - each resource uses a skill,
both earning experience for it and gaining a bonus to gathering/crafting speed dependant on the skill's level.
Skills, their levels, and the progress to a skill level up, are displayed at the top of the screen.

Note each skill has two types of levels, indicated by two numbers and two experience bars being present for each. 
The second of these is currently unused and does nothing, being intended for a future mechanic.

New resources are unlocked as the player progresses through the game. This can be done by:
Building certain constructions (the rightmost panel) - this is the main way unlocks occur
Levelling a skill high enough
Gathering/building a lot of a specific resource

The game is inspired by incremental/idle games, and should take a few hours to complete, though a significant portion of that may be idling rather than active gameplay.
Much less gameplay time than this is needed to get an idea of the game - almost all mechanics currently implemented are present from the start.
