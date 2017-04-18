---
layout: page
title: Portfolio
permalink: /portfolio
---
### Tabletop Design
The following is an assortment of design I've done for tabletop RPGs. This includes designing encounters and obstacles that are balanced, challenging and interesting, designing and playtesting new rules & systems, and creating/designing/writing coherent adventures that present the players with correctly balanced encounters and a central theme/objective.

The majority of this work uses the Symbaroum RPG system for the backbone. Additionally, there are some pieces of work that use Pathfinder and Fragged Empire RPG systems. There's a large backlog of content that I'm slowly adding to this portfolio. All of it can be found [over on Google Drive](https://drive.google.com/drive/folders/0Bwg2FcBAt_-7bXNxa1lxc2ZRMXc?usp=sharing)

___

### Style On 'Em (C#, Unity)
Style On 'Em is a turn-based fighting game created for the [#makeitSUPERHOT game jam](http://www.moddb.com/games/style-on-em). Style On 'Em is a game that rewards flashy combos. Players are awarded points depending on how stylish their combos are; the player with the most points wins, not the last player standing. You can also check the game out on [itch.io](https://ariimoose.itch.io/style-on-em)

This was a solo project, and free third-party assets were used for the animations and sound effects. For this project I worked on integrating all sound assets and animations, as well as designing and developing the gameplay systems; simultaneous turns, player input, attacking/blocking/dodging. By using delegate events I tied player actions to their respective animations and outcomes.

<div align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/1cB0SJm6ZKY" frameborder="0" allowfullscreen></iframe></div>

___

### Grapple Guys (C#, Unity)

A simple 2D brawler with a gimmick. In Grapple Guys players attempt to stomp on one another's heads with the use of grappling hooks! This is being developed as part of my Two Week Challenge, where I try to develop a game in 14 days. The finished prototype can be found [over at itch.io](https://ariimoose.itch.io/grapple-guys)!

For this project I relied on honing old skills, while learning new ones. The biggest hurdle for this project was delving into pixel art as a complete novice, as well as improving my UI Development skills. This project implemented some very basic gameplay logic, and applied very simple game rules. The most interesting part of the development was the game's centerpiece; the grappling hook. To develop this I used a third-party solution as a tutorial/starting point to better understand the mechanics. After that I modified the solution, working heavily with raycasts and the creation of joints to simulate the physics of the grappling hook's rope.

<div align="center"><iframe align="center" width="560" height="315" src="https://www.youtube.com/embed/CB5mznCfcIY" frameborder="0" allowfullscreen></iframe></div>

___

### Holdout (C#, Unity)

Holdout is a game for Android devices that combines RTS & Tower Defense. During my time working on Holdout I worked on a large variety of systems. The main focus of my work was AI. This implementing A-Star Pathfinding for player characters as well as targetting AI, and group AI for the enemy characters. Player character AI operated based on a priority list, where certain character types prioritised different tasks/targets. To optimise this the player character AI used several focal points. The player AI would ask a focal point for a particular type of target, the focal point would then return a suitable target from it's list of available targets. This reduced overhead from each player agent independently performing the same searches by shifting the search to one agent. The enemy group AI was the result of refactoring and optimisation. Instead of each enemy being autonomous they relied on the same focal points in a level that managed their AI and distributed commands.

In addition to AI I had a host of other responsibilities. One of these was integrating audio-visual assets (animations, 3D models, sound, particle effects). Another major role on the project was optimisation and testing. For a third of my duration with this project I focused on profiling and optimising the game for Android devices. During this I was also carrying out usability tests to ensure that everything worked in accordance with the design specifications.

<div align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/kE6iFrwtahI" frameborder="0" allowfullscreen></iframe></div>
___

### Tall Tales (Python, Natural Language Toolkit, Pyke, PyGame)

Tall Tales was a game engine prototype I developed as part of my college dissertation. It aimed to merge natural-language processing (NLP) mechanics directly into a game engine using knowledge engines. The project was planned, designed & developed in ~7 months. The project fell short due to me being ambitious and combining three very complicated topics into a project on a tight deadline. I did, however, get an amazing excuse to learn NLP outside of my college curriculum. This project taught me some serious project management and time management skills. On top of that I got to improve my Python skills, and expand my experience with knowledge engines and system architecture.

Unfortunately the tech demo does not do the project justice. The demo relies on a very system knowledge base, but in the background the user input is being tokenised, parsed, and interpreted by the language processor. The obfuscation of the project's functionality to the user makes it appear deceptively simple.

Once again, the project is [over at my Github](https://github.com/AriiMoose/Tall-Tales). If you're super curious you can [check out the dissertation](https://www.docdroid.net/VA2FWaD/andrewtullyfyp.pdf.html) on DocDroid

<div align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/BsKD6g6Sw58" frameborder="0" allowfullscreen></iframe></div>
___

### What Makes A Monster (Twine)
A last minute entry to Itch.io's Bite-Sized Horror game jam in 2016. What Makes A Monster is a short attempt at horror using Twine, and can be found [here](https://ariimoose.itch.io/what-makes-a-monster). This game, along with other entries in the game jam were covered by a small YouTuber by the name of Jupi. Unfortunately, this project didn't turn out as well as I would have liked. There are some spelling errors, and problems with the flow of scenes which could have been avoided by beginning work earlier.

<div align="center"><iframe align="center" width="560" height="315" src="https://www.youtube.com/embed/rerOewfTKnk?start=1112" frameborder="0" allowfullscreen></iframe></div>

___


### BGE (C++, OpenGL, BulletPhysics)

BGE is a game engine developed by my Game Engines lecturer, Bryan Duggen, which he used as a teaching tool. We spent a full semester studying the engine, using it for development, and also making modifications to it, as a learning exercise. The majority of this project relied on physics calculations using C++, as well as gaining an understanding of key game engine concepts such as quaternions, vector maths, and shaders. This concluded with us making physics-driven automotans powered by BulletPhysics & OpenGL. My automaton attempted to replicate the Tripods from War of the Worlds. Thanks to some mistakes with the motors powering the joints, it resulted in the Tripod jumping rather than walking.

The fork of the repository can be found [here on my Github](https://github.com/AriiMoose/BGE) with README explaining the thought process behind the project

<div align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/ii049d7UFrg?start=355" frameborder="0" allowfullscreen></iframe></div>
___

### Excalibur Quest Prototype (C#, SQLite, Unity)

A prototype of an Android companion app for a card-based adventure game. This was developed for a freelance client. The visual and gameplay design, along with the SQLite database, were supplied by the client. This project focused heavily on intregrating a local SQLite database with Unity, then pulling entries from the database using simple game logic and user input.

<div align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/58Q0OeHgsqk" frameborder="0" allowfullscreen></iframe></div>
