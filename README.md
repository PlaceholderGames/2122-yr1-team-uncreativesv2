# 2122-yr1-team-uncreativesv2
2021 CS1S464

## Contents
- [2122-yr1-team-uncreativesv2](#2122-yr1-team-uncreativesv2)
  * [Game Concept](#game-concept)
    + [Game Name](#game-name)
    + [Platform](#platform)
    + [Constraints](#constraints)
    + [Submitter](#submitter)
    + [Key Target](#key-target)
    + [Brief Description](#brief-description)
    + [Key Features](#key-features)
    + [Additional Selling Points](#additional-selling-points)
    + [Reference](#reference)
    + [Comments](#comments)
  * [Game Design](#game-design)
    + [Philosophy](#philosophy)
    + [Common Questions](#common-questions)
    + [Feature Set](#feature-set)
    + [The Game World](#the-game-world)
    + [The World Layout](#the-world-layout)
    + [Game Characters](#game-characters)
    + [User Interface](#user-interface)
    + [Weapons](#weapons)
    + [Musical Scores and Sound Effects](#musical-scores-and-sound-effects)
    + [Single-Player Game](#single-player-game)
    + [Character Rendering](#character-rendering)
    + [World Editing](#world-editing)
    + [Extra Miscellaneous Stuff](#extra-miscellaneous-stuff)
## Game Concept
### Game Name
Project: Sumi (Working title)
>[Notes on the name](https://en.wikipedia.org/wiki/Japanese_calligraphy) (Check the tools section)
### Platform
The game will run on windows x64 based machines, using a keyboard and mouse for inputs. A possible alternative to keyboard and mouse could be using Xinput controllers as Unreal supports those naitively and it shouldn't be too difficult to implement.
### Constraints
While we've now made a game in Unreal, and are on the whole feeling much more confident that with our first game, We still don't have much experience in 3D games, pathfinding or using C++ in unreal.
The deadline for this project is January 5th which gives us 7 Weeks to create a playable build.
### Submitter
Team Uncreatives, Consisting of Dylan Rees, Josh Hole, Mateusz Banachowski and Stuart Griffiths.
### Key Target
Project: Sumi (working title) Is a Hack and Slash adventure game where the player draws in their own battlefield through their attacks.
### Brief Description
The game will focus heavily on combat, and keeping combos while the player's attack will create areas of "ink" that will damage enemies and allow the player to use as platforms. This will make the player have to decide what types of attacks they want to use during combat, as large sweeping attacks will leave larger areas where they can no longer stand on. 
### Key Features
The player will have a diverse combo system at their disposal, stringing together different attacks to defeat their enemies.
Attacks will create lines of ink in the air, which the player can use as a platform or wall to gain a tactical advantage over their enemies.
The player will be graded on their preformance in real time, getting feedback on how well they are doing and could be rewarded with stronger attacks.
### Additional Selling Points
The game will have a oriental artstyle focusing on caligraphy during the Tang dynasty.
### Reference
>Encounter scale
<img src="https://omtl93h14or2oe6fzwxeik14-wpengine.netdna-ssl.com/wp-content/uploads/2019/08/gif.gif" width="444" height="250">

>Combat flow
<img src="https://thumbs.gfycat.com/OptimalAncientFurseal-size_restricted.gif" width="444" height="250">

>Artstyle
<img src="https://s3.gaming-cdn.com/images/products/2297/screenshot/game-steam-okami-hd-wallpaper-5.jpg" width="444" height="250">

### Comments

## Game Design
### Game Overview
#### Philosophy
This game doesn't have much in terms of an underlying philosophy. We just wanted to make a game we thought sounded cool.
### Feature Set
#### Common Questions
>What is the game?

Project: Sumi is a hack and slash adventure game where the player uses a brush as a weapon, which can be used to draw platforms into the world and affect the world around them. The player will travel through the various folating islands within the world with the quest of re-connecting the islands while solcing disputes between warring factions, and making a lot of allies along the way.
>Why make the game?

[Awnser](https://youtu.be/psKBsApwsDM?autoplay=1)
>Where does the game take place?

The game takes place in an as yet unnamed floating world, consiting of many scattered floating islands. Each island will have a unique look and feel, along with inhabitants and struggles.
>What do I control?

You control the currently unnamed protagonist character on their quest to re-unite the shattered islands of the world. The protagonist will use a brush as a weapon to attak their enemies and also create terrain that they can use to their advantage.
>What's the main focus?

The game will focus on the combat system extencively, with an emphasis on using creative and unique combos to dominate your opponents. The player will be rewarded for more "interesting" combos rather than just using the same attack over and over again.
>What's different?

In the market there is a noticible shift towards laregely story driven games and multiplayer games, with the biggest genres being FPS games. We thought a game focusing on the gameplay first would be a nice change of pace from the usual. We've also never seen a hack and slash game which creates terrain around the player dynamically.
#### General Features
#### Editor
#### Gameplay
### The Game World
#### Overview
#### World Feature (replace with actual world feature.
#### The Physical World
#### Rendering System
#### Camera
#### Game Engine
#### Lighting Models
### The World Layout
#### Overview
#### World Layour Details
### Game Characters
#### Overview
#### Creating a character
Undecided if this feature will be implemented, possibily in the future.
#### Enemies and Monsters
### User Interface
#### Overview
#### User Interface Details
### Weapons
#### Overview
#### Weapons Details
### Musical Scores and Sound Effects
#### Overview
#### Red Book Audio
#### 3D Sound
#### Sound Design
### Single-Player Game
#### Overview
#### Single Player Game Details
#### Story
Not of high-priority as of right now, will likely be explored further on in developed.
#### Hours of Gameplay
There's a planned endless mode, which will of course provided an indefinite amount of hours which can be played. There will be a planned story mode, but hard to quantify the amount of time it would require for completion.
#### Victory Condition
The endless mode will naturally not have a victory condition, althought there will be leaderboards for the players to try and beat. The story mode victory condition will be the player connect each of the islands together. 
### Multiplayer Game
#### Overview
There will be no actual tranditional multiplayer aspect of the game apart from leaderboards which the player will be able to compete against each other.
#### Customisation
The only available customisation which can be found by the player will be differing weapons and possibly character customisation (Still undecided if this feature will be included in the final product).
#### Persitence
The world will not be persistent.
#### Saving and Loading
Undecided, will discuss the idea later.
### Character Rendering
#### Overview
Cel-shading will be used for the character rendering, to give the characters a more stylised look and attempting to match the asthetics of Ōkami.
#### Character Rendering Details
The charcter rendering would ideally include cel-shading. Brief explanation: Using flat coloures in order to make an 2D object, while having 3D aspects. 
### World Editing
#### Overview
There will be light elements of world editing, where the player can create their own structures. 
#### World Editing Details
The player will be able to 'draw' platforms and barriers, which can be used for 'crowd control' of enemies and there will be a variety of different inks with special properities. There's also the proprosed idea of a special type of paint which will corriode the landscape, to create holes, trenches e.t.c. However, it's undecided if this mechanic will make it into the final product.
### Extra Miscellaneous Stuff
