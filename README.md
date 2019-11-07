# TetraForce
GBC Zelda-inspired game with online multiplayer. Built with Godot Engine

![TetraForce Logo](https://fornclake.com/wp-content/uploads/2019/10/tetraforce.jpg "TetraForce Logo")

TetraForce is a Legend of Zelda clone built with Godot Engine. It aims to combine classic Zelda gameplay with online multiplayer and a built-in randomizer.

We are currently trying to build a solid Zelda-like engine that can run online smoothly. The online multiplayer will be peer to peer connections with one central host server.

##### What is currently done (to be updated)
- Basic Zelda gameplay/combat
- Online multiplayer
- Screen transitions
- Dialog boxes

As of right now we have player and enemy synchronization finished. If players are in separate scenes, they will be running that scene client side with no network traffic. When a player enters a scene that another player is in, the first player will host that scene for the other player (and only that player). If the host leaves, it will be given to another player in that scene.

This should keep the networking light. If players are exploring different parts of the world, very little synchronization will be necessary. If they decide the join up, they will seamlessly connect.

No builds are out yet. In the meantime, feel free to download the source and play around with it. Current build is on Godot Engine 3.2 alpha 3.

##### The Team
- [fornclake](https://twitter.com/_fornclake "fornclake") - Project lead, programmer
- [TheRetroDragon](https://twitter.com/TheRetroDragon "TheRetroDragon") - Project lead, artist

##### Contribute!
We are looking for extra *programmers* to help with enemies, items, and everything else. If you have experience with Godot Engine (and especially Godot high level networking), please join us.

If you are a *composer* that can write GameBoy chiptunes, we would also love to hear what you can do.

Finally, *level designers* that can design Zelda overworlds and dungeons will be needed when we are further along in the project.

##### Join our Discord!
Join our Discord server for updates and discussion: https://discord.gg/cxTBVCZ

##### Instructions

Clone this github project 

Download Gadot for your OS (https://godotengine.org/download/)

Open Godot 
Click Import (in Godo Engine - Project Manager Window)
Enter path_to_project/project.godot (from step 1) (in the Import Existing Project Dialog Box)
Click Import & Edit
Press the play button on the upper right to enter the game
