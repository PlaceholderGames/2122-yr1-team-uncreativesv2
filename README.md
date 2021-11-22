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

Project: Sumi is a hack and slash adventure game where the player uses a brush as a weapon, which can be used to draw platforms into the world and affect the world around them. The player will travel through the various floating islands within the world with the quest of re-connecting the islands while solving disputes between warring factions and making a lot of allies along the way.
>Why make the game?

[Answer](https://youtu.be/psKBsApwsDM?autoplay=1)
>Where does the game take place?

The game takes place in a floating world called The Vast Expanse, consiting of many scattered floating islands. Each island will have a unique look and feel, along with inhabitants and struggles.
>What do I control?

You control the currently unnamed protagonist character on their quest to re-unite the shattered islands of the world. The protagonist will use a brush as a weapon to attak their enemies and also create terrain that they can use to their advantage.
>What's the main focus?

The game will focus on the combat system extensively, with an emphasis on using creative and unique combos to dominate your opponents. The player will be rewarded for more "interesting" combos rather than just using the same attack repeatedly.
>What's different?

In the market there is a noticeable shift towards largely story driven games and multiplayer games, with the biggest genres being FPS games. We thought a game focusing on the gameplay first would be a nice change of pace from the usual. We've also never seen a hack and slash game which creates terrain around the player dynamically.
#### General Features
Player created arenas.
Extensive Combo system
3D graphics
#### Editor
The player creates features in the combat area as they fight.
#### Gameplay
Key focus on the combat. The combat is the biggest focus in this game.
- The player gets access to 3 attacks, A light attack, a heavy attack, and a ranged attack.
- The attacks preformed change depending on how the user inputs prior, if they're in the air or not and the previous attacks.
- Depending on how varied and unique the combos are, the player will be rewarded with higher rankings and maybe higher damage
### The Game World
#### Overview
The world is divided into many floating islands, with each island having a unique biosphere. The area down below will not be explored in this game, but it could be hinted to as part of a final boss and explored in a future game. A lot of the islands can be explored with a few side quests and collectables dotted around.
#### Floating Islands
The game takes place on top of many islands floating in the sky. Each island was originally part of a single whole part but a misfire of a super-weapon long ago launched part of the continent into the heavens and the fragments remain. In the present, the people who live on the islands do not know about the world below and the game will not focus on it.
#### The world is magical
Elements of magic persist within the floating islands, the significance of which vary between the islands. In the starting island, magic is almost non-existent, while on other islands it could be the driving force behind their socio-economic hierarchy.
#### Mostly empty
Despite having nice set pieces, the world is mostly empty. The areas between the islands are called "The Vast Expanse" because it is largely empty. The islands are where the gameplay happens. The islands have a lot to collect and explore on them, but beyond the islands there's not much there as far as the player knows.
### The Physical World
#### Key areas
##### Tori Archipeligo
As the starting island, this island is largely peaceful. The archipelago is inhabited by the Tori village which at the start of the game only covers a single island. The village island is a dense forest with lots of rivers separating it, while the surrounding islands contain some more forest and a large grassy plateau. During the first part of the story the player will focus on connecting the village to the surrounding islands using their brush to resolve the village's overpopulation problem.
##### 
#### Rendering System
The game will have a cell-shaded art style with exaggerated outlines to show the rough and hand-drawn art-style. For rendering we will be using Unreal Engine's built in rendering system and using global shaders to handle the shading.
#### Camera
The camera will orbit the player and allow the player them to focus onto an enemy, keeping the camera behind the player panning it around the player.
#### Game Engine
To handle most of the low-level systems we will be using Unreal Engine version 4.25.4.
#### Lighting Models
The game will use a global illumination system, to allow more natural looking shadows and much more stylistic control. We be using standard vertex shading and rasterization techniques as most of the hardware should be able to run it, as opposed to if we made all of the lighting in the game be ray-traced.
### The World Layout
#### Overview
The player will start out on the Tori Archipelago, starting on the village island that will serve as a movement tutorial and quest hub. The player will then move out to the plateau island that will act as combat tutorial and help with teaching the player how painting works in a gameplay and story sense. Then the player will move out to another island, solve their unique problems, and connect the island to the Tori Archipelago. More details will be filled in later, but the demo won't go past the Archipelago.
#### World Layout Details
### Game Characters
#### Overview
The player character - a blank slate for the player to project themselves onto.
Clyde - A cheery childhood friend who's enthusiastic about building bridges. They call themselves "Bridge Builder Supreme".
#### Creating a character
Undecided if this feature will be implemented, possibility in the future.
#### Enemies and Monsters
Enemies might include an island's local fauna, or strange shadowy blobs that float towards the player.
### User Interface
#### Overview
The User Interface will contain a few key elements. Namely a health bar, an ink bar, and a style rating.
##### Health Bar
The bar will display the player's health as a percentage.
##### Ink Bar
This bar will show how much ink the player can draw with as part of their combo. This bar can be replenished by attacking enemies.
##### Style Rating
This will be a letter based grade that show how well the game thinks the player is doing. It will increase as the player pulls off more complex combos, and avoids getting hit.
### Weapons
#### Overview
The weapons in the game will all be exagurated drawing tools, Each tool has the ability to affect the arena the player is in.
##### Worldshaper's Brush
This magical brush was found in the ruins of a lost temple on Tori Island. It creates relatively quick and simple strokes of ink, which can be used as platforms or area-of-denial zones. This is the player's only weapon at the start of the game.
##### Whitesmith's Brands
This is a set of stamping tools which are very quick and short range. However, once an enemy is defeated, any stamps on them is launched off onto a nearby enemy dealing damage. This weapon doesn't do much in terms of creating terrain, but it should offer unique combat scenarios.
##### Skywrite's Steambrush
This is a relatively slow and wide area weapon, focusing on generating clouds of ink that damage enemies and allow the player to travel somewhat.
### Musical Scores and Sound Effects
#### Overview
Ideally, the game soundtrack would be dynamic and horizontally mixed to match the style rating of the player. Although we recognise that that could be outside of scope and budget, so some simple high action but traditional sounding music can be used. The sound effects can be either found from an online free library or recorded by the developers.
#### 3D Sound
To handle sound, we will be using Unreal Engine's built in sound system, which will handle 3D audio for us.
#### Sound Design
In terms of sound design we have no clue what we are doing, so we're just going to wing it.
### Single-Player Game
#### Overview
The game is a Hack and slash adventure game, where the player travels through the game world, fighting large groups of enemies to bring together all the shattered islands of the vast expanse. Each island the player travels will have a unique look and feel, along with collectables and side-quests. There will also be an endless mode where the player must simply defeat as many enemies as they can and survive for as long as possible.
#### Story
Not of high priority as of right now, will likely be explored further on in developed.
The player starts of on Tori Island. It is a heavily forested island with another island not to far away, the player's village is bustling but the player is informed by the village elder that the island they're on is too crowded, and they need more space beyond this island to expand their farms to sustain everyone. But seeing as there is no way to expand the island, they might have to resort to desperate measures. This is where the player character would run away from the village and stumble into an ancient ruin, where they find the brush weapon than can create physical objects by just painting. The player character then makes their way across to a nearby island where they make their first combat encounter.
#### Hours of Gameplay
There's a planned endless mode, which will of course provide an indefinite number of hours which can be played. There will be a planned story mode, but hard to quantify the amount of time it would require for completion.
#### Victory Condition
The endless mode will naturally not have a victory condition, although there will be leader boards for the players to try and beat. The story mode victory condition will be the player connect each of the islands together.
### Multiplayer Game
#### Overview
There will be no actual traditional multiplayer aspect of the game apart from leader boards which the player will be able to compete against each other.
#### Customisation
The only available customisation which can be found by the player will be differing weapons and possibly character customisation (Still undecided if this feature will be included in the final product).
#### Persistence
The world will not be persistent.
#### Saving and Loading
Undecided, will discuss the idea later.
### Character Rendering
#### Overview
Cell-shading will be used for the character rendering, to give the characters a more stylised look and attempting to match the aesthetics of Ōkami.
#### Character Rendering Details
The character rendering would ideally include cell-shading. Brief explanation: Using flat colours in order to make an 2D object, while having 3D aspects.
### World Editing
#### Overview
There will be light elements of world editing, where the player can create their own structures.
#### World Editing Details
The player will be able to 'draw' platforms and barriers, which can be used for 'crowd control' of enemies and there will be a variety of different inks with special properties. There's also the proposed idea of a special type of paint which will corrode the landscape, to create holes, trenches etc. However, it's undecided if this mechanic will make it into the final product.
### Extra Miscellaneous Stuff
