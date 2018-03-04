# Jet Set Willy 3: A New Beginning

![Logo](https://github.com/LBruni98/Jet-Set-Willy-3-The-Unofficial-Sequel-/blob/master/Jet%20Set%20Willy%203%20Logo.png)

All work Copyright ©2018 by Reboot Games

Written by Luke Bruni

## Table of Contents

```
1. Project Management
  1.1 Revisions
  1.2 General Aims
    1.2.1 Main Objective
    1.2.2 Secondary Objectives
  1.3 Requirements
    1.3.1 Scope
    1.3.2 Resources
      1.3.2.1 Unity
      1.3.2.2 Firebase
      1.3.2.3 Internet Access
      1.3.2.4 Appropriate Computer
    1.3.3 Cost
  1.4 Project Schedule
  1.5 Risk Assessment
    1.5.1 Scope Creep
    1.5.2 Hardware/software issues
    1.5.3 Cost Management
  1.6 Contingency plans
    1.6.1 Scope Creep
    1.6.2 Hardware/software issues
    1.6.3 Cost Management
  1.7 Feasibility Report
    1.7.1 Technical Feasibility
    1.7.2 Market Feasibility
  1.8 Development Aims
    1.8.1 Movement
    1.8.2 Combat
    1.8.3 Collision
    1.8.4 Items
    1.8.5 Enemies
2. Design Document
  2.1 Revisions
  2.2 Game Overview
    2.2.1 Philosophy
      2.2.1.1 Revival
      2.2.1.2 PC and beyond…
    2.2.2 Common Questions
      2.2.2.1 What is the game?
      2.2.2.2 Why create this game?
      2.2.2.3 Where does the game take place?
      2.2.2.4 What do I control?
      2.2.2.5 How many characters do I control?
      2.2.2.6 What is the main focus?
      2.2.2.7 What’s different?
  2.3 What’s in a Game
    2.3.1 Gameplay Overview
    2.3.2 Money
    2.3.3 Punch Ups
    2.3.4 Platforming
  2.4 The Mansion
    2.4.1 Overview
    2.4.2 Non-linear
    2.4.3 What’s in the mansion?
      2.4.3.1 Overview
      2.4.3.2 Key Locations
      2.4.3.3 Scale
    2.4.4 Game Engine
      2.4.4.1 Overview
      2.4.4.2 Sprite Management
      2.4.4.3 Animation
    2.5 Game Characters
      2.5.1 Main/Playable Characters
        2.5.1.1 Miner Willy
        2.5.1.2 Andre the Chef
        2.5.1.3 Maria
        2.5.1.4 Brother Geoff
        2.5.1.5 Brian
      2.5.2 Enemies and Monsters
        2.5.2.1 The Taxman
    2.6 User Interface
      2.6.1 Overview
      2.6.2 HUD
    2.7 Control
      2.7.1 Methods
      2.7.2 Direct Control
    2.8 Single-Player Game
      2.8.1 Story
    2.9 Multiplayer Game
      2.9.1 Overview
        2.9.1.1 Max Players
        2.9.1.2 Customization
        2.9.1.3 Internet
3. Security Report - Reducing Vulnerabilities During Development
  3.1 Introduction
    3.1.1 Software Development
    3.1.2 Vulnerabilities
      3.1.2.1 Types of Vulnerabilities
  3.2	Case Studies
    3.2.1 Yahoo 2013-2014 Data Breach
    3.2.2 NHS Cyber-Attack
  3.3	Mitigating Software Vulnerabilities
  3.4 Conclusion
  3.5 References
4. Evaluation
  4.1	Testing Report
  4.2	Evaluation 
  4.3	Critical Analysis
  4.4	Future changes
```

## 1. Project Management
### 1.1 Revisions

|Version|Name        |Date       |Notes                                                  |
|-------|------------|-----------|-------------------------------------------------------|
|1.00   | Luke Bruni |05/02/2018 |Initial Document                                       |
|1.10   | Luke Bruni |18/02/2018 |Heading and section changes along with more information|
|1.11   | Luke Bruni |18/02/2018 |Information added to .DOC version                      |

### 1.2 General Aims
#### 1.2.1 Main Objective
The main objective of this project is to create a rebooted version/sequel of the game 'Jet Set Willy'. The aim is to create this game with more features and a revitalised gameplay style.

#### 1.2.2 Secondary Objectives
One aim during this project is to gain more experience of the Unity engine and to get to know other tools that would be beneficial to the project, such as firebase, a database software that will be used for the multiplayer aspect.

### 1.3 Requirements
#### 1.3.1 Scope
The game is labelled to be a sequel and will have a newer style to keep the game looking refreshed and not the same visually. As part of the newer features, the feel of Jet Set Willy must remain and shouldn't deviate too far from the original game.

Jet Set Willy 3 will have a newer platforming system, more towards a modern audience with fluid control and good responsiveness, rather than the old system, which made the game difficult in some places and often impossible to clear. This should bode well with the newer mechanics of the game such as the constant scrolling and the faster gameplay.

Combat will be included to provide some action to the game. The player can punch, perform some combos and probably do some finishing moves, though this won't be the main aspect of the game, as the features must not spoil too much of the original formula. Enemies will be tough and the player can be easily overwhelmed, so avoidance is key.

#### 1.3.2 Resources
The required resources are as followed:

##### 1.3.2.1 Unity
The game will be developed in unity, reasons being that I have past experience of using the engine and that it has features that can help me with developing the game.

##### 1.3.2.2 Firebase
Firebase will be used for the games multiplayer aspect, with features contained that are common with most game hosting servers. The players data will be stored on the firebase database and tools that allow for players to be a assigned a space in a game. Conveniently, Firebase can be used with Unity with it's own features for monitoring players and messaging. 

##### 1.3.2.3 Internet Access
Internet access will absolutely necessary because research will be carried out in this project; secondary research by reading articles and webpages and primary research with web serveys and such. This will also be used to keep track of analytics of players in multiplayer games and to test the multiplayer portion of the game, as well as eventual publishing of the game.

##### 1.3.2.4 Appropriate Computer
At least a decent computer must be used in order help with the development of the game. The computer must be matching the minimum requirements of the software that will be used during development and to make sure that it can run well without issues.

#### 1.3.3 Cost
The platform I am developing is for PC where it is free and requires no developing license whatsoever. Unity Pro which is the engine that will be used will come at £125 a month. Development of the project will take around three months so that will add up to £375. The version of Firebase that will be used is entirely free, containing the features that I need so there will be no upgrading.

The PC for home development will be my own system priced at the time at £789. A secondary PC for home development will also be used for writing up documentation or for backup, which costs £300.

The internet that will be used cost £45 a month which as mentioned earlier with the amount of time for development will cost £135 for three months.

The overall cost of this project will add up to £1,599.

### 1.4	Project Schedule
![Gantt Chart](https://github.com/LBruni98/Jet-Set-Willy-3-The-Unofficial-Sequel-/blob/master/Gantt%20Chart.jpg)

### 1.5 Risk Assessment
#### 1.5.1 Scope Creep
Original objectives and ideas may gradually expand to the point where the project may take far longer or have a possibility of failure. Scope creep may happen because of poor understanding of the original project, changes within the market or even competing forces within a company.

#### 1.5.2 Hardware/software issues
Issues here maybe storage devices are missing, damaged or corrupt files, that hinder the project greatly because of important files becoming unavailable, having to start again from scratch. The PC or router would be damaged or flat out stop working, causing huge delays in the project until they are repaired or replaced.

#### 1.5.3 Cost Management
During the project, issues such as lack of software or, in an unlikely case, changing ISPs to help with the internet may interfere with the original budget and cashing out for features or software for the product, with the risk of the project going over budget and the project failing because of it.

### 1.6	Contingency plans
These plans are actions to the aforementioned risks above.

#### 1.6.1 Scope Creep
To prevent the risk of scope creep, ideas will be set and seen that they are followed with no major change. Any minor change is allowed, but with careful consideration, so factors like timelines are reworked slightly or more time is given to allow for this change. This in turn should help prevent any extreme scope creep.

#### 1.6.2 Hardware/software issues
Storage backups will be used in case of any failure to the storage devices mentioned in 1.5.1. There will also be backup storage of the backups in case of an extreme outcome of the risk. In regards to internet failure with the router being broken, again the backups will help should there be any cloud files that cannot be accessed and the research portion of the project will be carried out first as hopefully the development of the game doesn't require internet connection, even the multiplayer portion. As mentioned in 1.3.3, there are two computers, the software can be installed on both computers with the same license so should a computer break down, the other will be used in place so the project can continue.

#### 1.6.3 Cost Management
In case of the cost going too high, an extra amount is kept until anything comes up. This amount accounts for about half of the original budget. Also, the aims were considered carefully based on what I could use and the purhcases were already made.

### 1.7	Feasibility Report
#### 1.7.1 Technical Feasibility
The deliverables are to address the development properly and to show the game's progress. The project timetable being set and deliverables will be delivered at the end of each development iteration, such as documentation, design, testing, etc. so development won't be too built up and left until the last minute. The project will use the Unity engine for development because of the features that it contains that would prove beneficial to the development of the game and other seperate features that are compaitible with Unity, such as firebase, database software from google that will aid in the multiplayer aspect of the game, this alluding to the ease of using Unity.

#### 1.7.2 Market Feasibility
The growth of more retro looking titles has grown exponentially and more or less the need of these types of games have been growing. These sorts of games follow more faster paced but older looking games, stuff that would've looked possible at the time but would be of modern gameplay and performance. Being that this game is a sequel, it will look more retro but not exactly like the older games and be more faster paced than the games before it because of the performance of modern machines. This in turn should put a foot in the door to the retro genre of games as said genre does perform very well and being a sequel of older games, it should draw more of an attention towards older fans of the game.

### 1.8	Development Aims
#### 1.8.1 Movement
| User Story | Task Description                             | Points |
| ---------- |--------------------------------------------- | ------ |
| 1          | Moving left and right                        |   1    |
| 2          | Character Movement Speed                     |   1    |
| 3          | Jumping                                      |   1    |
| 4          | Ducking                                      |   1    |
| 5          | Key bindings                                 |   2    |

#### 1.8.2 Combat
| User Story | Task Description                             | Points |
| ---------- |--------------------------------------------- | ------ |
| 1          | Punching                                     |   2    |
| 2          | Blocking                                     |   2    |
| 3          | Finishers                                    |   3    |
| 4          | Combo counter                                |   2    |

#### 1.8.3 Collision
| User Story | Task Description                             | Points |
| ---------- |--------------------------------------------- | ------ |
| 1          | Character contact with ground                |   2    |
| 2          | Hitboxes                                     |   2    |
| 3          | Hazards                                      |   3    |
| 4          | Health                                       |   1    |

#### 1.8.4 Items
| User Story | Task Description                             | Points |
| ---------- |--------------------------------------------- | ------ |
| 1          | Item functionality                           |   2    |
| 2          | Money Counter and Quota                      |   3    |
| 3          | Interaction                                  |   1    |

#### 1.8.5 Enemies
| User Story | Task Description                             | Points |
| ---------- |--------------------------------------------- | ------ |
| 1          | Pathing                                      |   2    |
| 2          | Detecting the player                         |   5    |
| 3          | Enemy Health                                 |   3    |

### 1.10 Backlog
#### 1.10.1 Week 1
#### 1.10.2 Week 2

## 2. Design Document
### 2.1 Revisions

|Version|Name        |Date       |Notes                                          |
|-------|------------|-----------|-----------------------------------------------|
|1.01   |	Luke Bruni	|20/12/2017	|Initial Document                               |
|2.00   |	Luke Bruni	|08/01/2018 |Complete Rewrite                               |
|2.10   |	Luke Bruni	|30/01/2018 |Document Transfer (.DOC file to README.MD file)|
|2.11   |	Luke Bruni	|31/01/2018 |Numbered lists for easier navigation           |

### 2.2 Game Overview
#### 2.2.1 Philosophy
##### 2.2.1.1 Revival
The game is trying to capture the original essence of the Jet Set Willy and Manic Minor games and hopefully bring the series back to full form towards a more modern audience.

##### 2.2.1.2 PC and beyond…
The series were developed for a variety of PCs at the time, which unfortunately such platforms doesn’t exist anymore, where the operating system is the same and the variety comes from the user designing their own dream PC. The aim is to design the game for PC and broaden the horizon of the game towards more platforms, such as Xbox One, PS4, etc.

#### 2.2.2 Common Questions
##### 2.2.2.1 What is the game?
The game is a sequel to that of the 2nd Jet Set Willy game (Not counting the Perils of Willy). A platformer that aims to take the original and build upon it for the modern audience, while reaching out towards the older fans of the game.

##### 2.2.2.2 Why create this game?
As well as develop for the Reboot Games site, the aim is to bring back one of Britain’s old gaming icon of the 80s, bring him to a more modern audience and make a game that would improve upon the formula of the older games.

##### 2.2.2.3 Where does the game take place?
The game takes place in his larger-than-life, bizarre mansion that is made of his wildest dreams. The player can explore it all with no locked areas, straight from the get-go.

##### 2.2.2.4 What do I control?
The player controls Miner Willy, a playboy and self-retired miner. The player can traverse the mansion, such as a traditional platformer and the older games of the series, however the player can now fight but only when within certain situations.

##### 2.2.2.5 How many characters do I control?
The player can not only control Willy, but also some other characters, such as the mansion’s chef Andre and the maid Maria, to name a few. The characters are unique in terms of animation but don’t have any special abilities. These characters are unlocked over the course of the game.

##### 2.2.2.6 What is the main focus?
The game is about Willy, having a visit from the Taxman after a wild party. The taxman has had enough of Willy skimping payments and has threatened to end his riches if Willy doesn’t pay all his remaining taxes.

##### 2.2.2.7 What’s different?
Unlike more common platformers, it’s bringing back the non-linear style that was present within the old games. A style more prominent in games such as Bioshock, a first-person shooter, and numerous RPGs.

In comparison with this game and the older games, the platforming is revamped to reflect on much quicker gameplay and to keep up with the quicker gameplay seen in most games today, deviating on the slower gameplay of the original games.
 
### 2.3 What’s in a Game
#### 2.3.1 Gameplay Overview
The gameplay will match the original nonlinear style of the game where the player can explore all his mansion at will and take different approaches to getting to the goal. To help with the exploration, the game is not divided into “rooms” (The game's not “flip-screen”).

The game takes the same approach to collecting items, but rather than the item negating from a counter the amount of money found inside that item or the value of that item will add to the money counter. The money takes on many forms, like stated before, money can be picked up inside objects in the house or found in various places. Money is more the aim here and Willy must collect enough money to fulfil a quota. This quota will change and the game will change along with it, altering some of the levels. Quotas will keep being fulfilled to progress the game's story until the end

#### 2.3.2 Money
A notable change in the objective will be what is needed to complete the game. Money is now the aim of the game instead of collecting items in the older games and is needed to fulfil the quota of the taxman.

Money can be found around the mansion, either in obvious places, items, cabinets or in specific areas. The money in the game can have various amounts depending on where the money is found, for instance:

* Found areas: £50 - £200
* In cabinets, dressers, closets, etc.: £1000 – £5000
* In items: At least £800

Specific areas trigger events to which the player can complete to earn a good pay-out from them (At least £10,000). However, the player could be met with consequences to which they would need to avoid them.

Once Willy has met an objective amount, newer events will happen such as newer stuff getting added or the game will begin to get harder. This will continue until the end of the game.

#### 2.3.3 Punch Ups
Willy can now fight, throw punches and knock enemies out. Sure, blood may be spilled along the way, but the combat won't be a staple in the mechanics (there won't be any weapons as well), being that the game focuses in the platforming, where fighting will be as a last resort or saved as part of a certain mission.

#### 2.3.4 Platforming
His platforming ability has improved immensely; he can grab ledges, run, duck and roll, which should add some tense action to traversing the mansion.

### 2.4 The Mansion
#### 2.4.1 Overview

The mansion is Willy’s prised home and the result of his mining success. The entire place along with Willy’s personal possessions are at risk of being repossessed by the taxman, so it is up to him to save everything before that happens.

The mansion is larger than life, but rather a small, quaint home to Willy. Contained within it are bizarre rooms and things; some dangerous and some unknown to Willy.

#### 2.4.2 Non-linear
Following the non-linear style of the game and the games before it, the entire mansion can be explored at will, right from the get go and no areas that need to be unlocked. No catches, no items required to enter a room, just the freedom to roam about and explore the mansion as much as we can at any time.

#### 2.4.3 What’s in the mansion?
##### 2.4.3.1 Overview
The mansion is built up of various rooms that the player can take many routes to get to. They all consist of platforms of various size and properties, much like the game’s precursors.

As the game goes on, the rooms may change along the way depending on the playthrough; there could be a new enemy that appears in the rooms or an entire room may be blown to bits for reasons of plot (or not!).

##### 2.4.3.2 Key Locations
*	Banyan Tree – The original tree all in its glory, a pain to get through on the original game, but will now be redesigned to be easier to get through.
*	MegaTree – The tree in the front yard of the mansion, where Willy can explore for money and then can head off to the off-license if he gets bored. This area will be larger for the player to explore and to add more challenge. In homage to the unfinished third game in the Miner Willy series.
*	Entrance to Hades – This time it WILL be Hell!

##### 2.4.3.3 Scale
The world will be large, larger than the original games and newer areas will be added along with the original ones.

The room names will come up to show the user where they are, which should help navigation.
If the user is REALLY lost, then a map can be used to find out where the user is, which will be in the style of floor plans/blueprints.

#### 2.4.4 Game Engine
##### 2.4.4.1 Overview

The engine used to create the game will be in Unity. Unity was chosen because it has very good 2D compatibility and good, recent knowledge of the engine. Other features of this engine below.

##### 2.4.4.2 Sprite Management
Working with sprites in unity are easy to work with. Sprites can be assigned various properties for various features such as animation and multiple sprite sheets. A sprite editor can be used for use of sprite slicing for animations or menus.

##### 2.4.4.3 Animation
Unity has numerous features for managing animation. The engine has two methods of animations; frame by frame and through a curve editor, but for 2D animation, frame by frame is necessary. The engine uses both animation controllers for individual actions and a timeline for cinematics, which use the animation files from the animator mentioned earlier.

### 2.5 Game Characters
#### 2.5.1 Main/Playable Characters
These characters can be unlocked over the course of the game and can be switched out during gameplay. These playable characters can be used in the multiplayer aspect of the game.

##### 2.5.1.1 Miner Willy
The player takes control of the main character, Miner Willy. A semi-retired miner and playboy, owner of a large mansion filled with bizarre things and generally where he spends all his life in.

##### 2.5.1.2 Andre the Chef
The mansion’s chef. Mostly laid back, hardly works because of poor pay checks, going mostly to Willy. Gets involved in Willy’s debt at one point.

##### 2.5.1.3 Maria
The mansion’s housekeeper, always tired with Willy’s antics, ultimately rules the mansion with an iron fist, or so she thinks

##### 2.5.1.4 Brother Geoff
Overly religious pastor that runs the chapel inside Willy’s mansion. Claims to be a man of the lord but manages to open a portal to Hell.

##### 2.5.1.5 Brian
Willy’s annoying friend that manages the off license located nearby, just after the MegaTree. There mainly to “help” Willy and has a pint with him most of the time.

#### 2.5.2 Enemies and Monsters
The enemies in Jet Set Willy 3 are far random, dependant on the room that willy could go in or some that just come up from time to time. The main enemies that Willy will encounter alongside these enemies and static hazards:

*	Repo Men
*	Party Goers
*	The Taxman himself!
*	And many more!

##### 2.5.2.1 The Taxman
The man that people hate. An overbearing, obnoxious person that would only think of himself. Slick hair and a long overcoat and would do anything to get money from people. Often, he would go into a fit of insanity and would beat people up, should they cross him.

He comes prepared with a unit; heavy repo men that would come to trash the place to collect money or valuable objects to pay off a debt if the person doesn’t pay. These people can’t be knocked down and Willy would need to avoid them most of the time, though he can stun them for a bit.

### 2.6 User Interface
#### 2.6.1 Overview
As the game is mainly derived from its prequels, the interface should be simple enough for the user and not be needlessly complicated at all. Menus are simple, being there will be some options to configure and something for the extra features; a basic main menu system with some extra aesthetics that match the design of the game.

#### 2.6.2 HUD
Regarding the UI for the initial game, it will function similarly to that of the original games. i.e. the location names and objectives (items collected in the old games, money in this sequel). The HUD will be updated and designed to allow for the game to be centre stage and not take up a portion of the screen.

### 2.7 Control

#### 2.7.1 Methods
The players can have two methods of control, by that of using keyboard or using a controller for the PC using the default button maps. An Xbox controller will be used for testing and will be the basis for other plug in controllers and other platforms.

Both users will have the opportunity to change the button maps of to their own playstyle, should the default layout not be suitable for them.

#### 2.7.2 Direct Control

|Action     |Key binding (Default PC)    |Controller (Default Xbox One) |
|-----------|----------------------------|------------------------------|
|Move Left	 |'A'                         |Left Analogue Stick/DPad Left |
|Move Right	|'D'                         |Left Analogue Stick/DPad Right|
|Jump	      |'W'                         |A Button                      |
|Duck	      |'S'                         |B Button                      |
|Roll	      |SHIFT                       |Y Button                      |
|Punch	     |Left Mouse                  |Right Trigger                 |
|Block	     |Right Mouse                 |Left Trigger                  |
|Interact	  |'E'                         |X Button                      |
|Pause	     |ESC                         |Start Button                  |

### 2.8 Single-Player Game
#### 2.8.1 Story
> Willy is back after a long relaxing break, but it's not the comeback he was expecting. After a huge party, a hungover Willy gets a visit from a nemesis: The Taxman! After skimping on his taxes and cashing out on necessities for himself, it turns out that the taxman is gonna get his sick dream of repossessing ol' Willy. Now, our hero must scrounge his own bizarre, party ridden mansion to find his money or the taxman will take all of what he has earned!
**– Offical Summary**

The story begins with Willy waking up from a dream of him in the old game style, which is the original ending for Jet Set Willy; heading for bed, but then heading into the bathroom and getting stuck in the toilet.

He gets a knock on the door and goes down to answer it, revealing the taxman, looking smug with himself with his henchmen close by. He explains to Willy, with a couple of jokes, that he has been skimping out on payments to him to which he only has a limited amount of time to gather over £25,000,000 to pay off, or “He’ll break your teeth in”.

A glum looking willy now must collect his amount each time or his place gets torched, but gets an idea to look throughout the whole of his mansion to find every little amount, regardless if it kills him or not.

Throughout his adventures Willy finds money in all locations until he is hit with a problem, that he still lacks it for a required amount. He then goes down to Andre in the kitchen, who tells him a party goer is keeping a required amount to which Willy must get the money back from. He heads up there to find Brian, drunk and violent, carrying the money. After a confrontation that gets Brian sober, he gives him the money to which he responds with “Whatever” and Willy gives the amount to the Taxman, who is contempt in Willy’s findings but then says to him that its only just begun…
 
### 2.9 Multiplayer Game
#### 2.9.1 Overview
The multiplayer game aspect is a different version of the single player game, where the players take control of various characters and must collect money to a time limit. It’s more of a faster paced version where players must go separately or in groups to help collect money and survive the mansion.

The multiplayer section will be simple, with no levelling and such but with the choice of character that they can play. All the user has to do is make sure he/she has internet and they can just jump in and play!

##### 2.9.1.1 Max Players
The game can have anywhere from 2 players up to 12 and local multiplayer can be used for online play as well.

##### 2.9.1.2 Customization
The players can choose ANY character that is seen in the main game, this includes main characters, side characters and enemies. They don’t have unique abilities but have unique personalities that should add to the overall design experience.

Players can also chat in game to each other which comes up in a box but also a speech bubble if close by.

##### 2.9.1.3 Internet
The servers will be Listen servers, which give benefits of what dedicated servers have but should allow for quicker games. However, because of the type of game this is for multiplayer, other investigations will commence.

## 3. Security Report - Reducing Vulnerabilities During Development
### 3.1 Introduction
#### 3.1.1	Software Development
Software development is the process of creating applications or software which is made using a specific programming language. This is an iterative process used to create these programs, to fulfil either a business or personal goal, process or objective. The process is usually made up of various steps within development to create the operational software in question.

The method of creating software is commonly referred to as a Software Development Life Cycle (SDLC) and the process is normally carried out through the software programmer, with initial research, data and process flow design, flow charts, technical documentation, testing and debugging. The process is commonly iterative, but there are other methodologies to adopt depending on the nature of the program [1]. 

##### 3.1.1.1	Software Development Process
All Software Development Life Cycle models have phases which are in the order that they are executed in. Each phase marks a point for the deliverables which are required by the next phase. Every Lifecycle model has these six development phases:

1. Requirement gathering and analysis
2. Design
3. Implementation or coding
4. Testing
5. Deployment
6. Maintenance [2]

##### Requirement Gathering and Analysis
This phase is where the requirements are collected and understood and is the main focus of the project managers and stake holders. Meetings are held in order to determine the requirements, with questions considered in relation to the software’s purpose, such as who is this system built for? Who will use the system? How will they use it? Etc. where then these requirements are analysed for the purpose of validation and use within development.

It is relatively important to gain these requirements because it sets the development of the project in stone. Each member of the team has a solid understanding of the product in their minds, so they can build of what they are given, supporting the next phases of development. To perfectly understand what the requirements are, it should be important to keep them clear and concise, that way a good understanding is used and the requirements can support the development [3].

![Management](https://github.com/LBruni98/Jet-Set-Willy-3-A-New-Beginning/blob/master/Project%20Management.png)
>Figure 1: Tree Swing Project Management Comic [4]

The requirements to a project are heavily based on how they are perceived, as mentioned previously. Should the team not understand the requirements, then they won’t prove beneficial to the development and would more often result in the project being designed without the requirements in mind, confusion amidst each team member and ultimately leading to a product that the client didn’t ask for. The figure above showcases a simplified view of mishandled or misunderstood requirements.

##### Design
The system design is then prepared based on the requirements in the previous phase. The design helps in specifying the hardware and defining the overall system architecture, setting in place the next stage of development.

It is also worth noting that testers involved come up with a test strategy, detailing what to test and how to test it.

##### Implementation or Coding
When the design documents are completed, the work is then split up into units and modules and the actual coding starts. This phase is the main focus as it is where the features are implemented and the code is produced and it is also worth noting that this is the longest phase out of the entire development lifecycle.

##### Testing
After the code is developed, the initial product is tested against the requirements to make sure that the product meets the client’s needs and serves its purpose as stated within the first phase. All types of testing are carried out, such as unit testing, integration testing, system testing and acceptance testing as well as non-functional.

##### Deployment
This phase comes after successful testing, the product is then handed over to the product to see if said product fulfils the goals that were asked. As soon as it is deployed, the first beta testing will commence, where any changes requested are noted and bugs are discovered. The outcome of the beta testing will serve as a basis for the final release.

##### Maintenance
When the customer uses the system, problems will arise from time to time and would need to be solved. Care is taken for the developed system to ensure it still operates perfectly without any faults.

#### 3.1.2	Vulnerabilities
Regarding computing security, vulnerabilities are weaknesses within software, being a flaw within code or design that creates an opening for an attacker to breach security and either run code or access a system’s memory. Because these vulnerabilities are discovered, they are then exploited, allowing to be conducted through hacking scripts, applications or even free hand coding [5]. Once the attacker has breached access, they have the opportunity to gain access to information and can exploit the vulnerability to hide their actions [6].

##### 3.1.2.1	Types of Vulnerabilities [7]
This section describes each vulnerability that could occur in software.

###### Buffer Overflow
A buffer overflow is where an application attempts to write data past the end of a buffer. This can cause the program to crash, compromise data and provide an attack vector to compromise the system.

Applications that take input from the user, from a file or a network has to store that input. This storage is temporary, but there are two exceptions to where it can be stored, in either the stack or the heap. Buffer Overflow attacks occur by compromising either one storage or both.

###### Unvalidated Input
This is unwanted input that can occur by having the attacker interfere and pass in abnormal data. Once the program crashes, then the attacker looks for exploits in the system and subsequently take control of the system, steal data, corrupt disk, etc.

Any form of input from an untrusted source is a more than likely target for an attack, such as:
•	Text input fields
•	Commands passed through a URL used to launch the program
•	Files provided by users or other processes and read by the program
•	Command line input
•	Any data read from an untrusted server over a network
•	Any untrusted data read from a trusted server over a network.

###### Race Conditions
Race conditions are made when changes in events cause a behavioural change, to which the attacker can take advantage of the situation to either insert their code, change the name of a file or just interfere with the program’s operation. However, this may not always be the case, as if the correct order of execution is required for the operation of the program, then the change is a bug.

###### Interprocess Communication
This is a mechanism that allows for data exchange between processes [8]. The methods involved include shared memory or a messaging protocol such as sockets. These messaging protocols are vulnerable as the end communication channel could be hostile, so programmers have to always assume that they are hostile.

###### Insecure File Operations
An attacker can change the permissions of a file after creation, if not checked properly. This is the result creating insecure temporary files and can result in tampered files that the owner wouldn’t notice [9].

###### Access Control Problems
Access control is the process of controlling who can do what. This can be access to certain files or resources in a computer and what they can and can’t do with those resources or files
 
### 3.2	Case Studies
#### 3.2.1 Yahoo 2013-2014 Data Breach
Recently, Yahoo had said that all 3 billion of its accounts were hacked in a data theft that had occurred in a disclosure during the company being sold to Verizon. It had been the biggest breach in history, tripling its earlier estimate [7].

An investigation was carried out in 2013 saying that 1 billion accounts were compromised, but went unnoticed. Yahoo did blame the breach on an “Unauthorized third party”, though most details weren’t provided until law enforcement had reported that the files were originally from yahoo but a third party had managed to obtain the files. The company had then verified that the stolen data was legitimate shortly after.

The data that was affected was mainly user data; names, emails, phone numbers, dates of birth and hashed passwords were obtained, mainly because they were protected with outdated encryption which was considered easy-to-crack and security questions along with backup email addresses, to which it was easy to break into the other accounts that were held by the users. However, the investigation had specified that the stolen information did not include payment card data or bank account information [8].

Another investigation was carried out, reporting another massive breach which affected 500 million in 2014 but botched its response. The security team at Yahoo had knew about what Yahoo report as a ‘state-sponsored hacker’ had stolen backup copies of backup files, containing personal details on users. The reason it was finally brought to light, two years after the breach, was because of a stolen database purportedly went up sale on the black market [9]. 

It wasn’t until much recently that additional information had been obtained by Yahoo, where it showed that all user accounts had been affected, the 3 billion figure including accounts that were opened but never or briefly used. In response, Yahoo emailed notifications to additional users that were affected.

The following breaches had affected a deal with Verizon where following the newer information about the first breach, lowering it by $350 million from Verizon’s original offer to buy the company and brought about 43 class action lawsuits against Yahoo. The original deal had closed in July 2017.

#### 3.2.2 NHS Cyber-Attack
NHS trusts were hit by a huge ransomware attack in May 2017, where more than a third of the trusts throughout England and Scotland were disrupted by the ransomware. As a result of this, at least 6,900 NHS appointments were cancelled but no data relating to patients was compromised. There was no evidence that any NHS organisation paid the ransom but the cost of the incident remained unknown [10].

The Ransomware in question was called ‘WannaCry’. A file encryption software, that encrypts the PCs files, that prevents user access to the PC and demands a payment to be made, in bitcoin, to decrypt them, usually demanding $300 in bitcoin. The Vulnerability that WannaCry exploits is in the Windows implementation of the Server Message Block (SMB) Protocol, which helps nodes on a network communicate [11].

The issue was that out of 236 trusts, 88 had failed the required cyber-security standards and a lack of action on critical alerts from NHS digital. Computers at the NHS were running the old Windows XP operating system, which were vulnerable due to the stopped support on 8 April 2014 [12]. A patch had been brought out but it was also discovered that also the Windows 7 OS was vulnerable, but that operating system was still supported. A plan was developed to help counteract such attacks, it wasn’t seen through properly, with poor management, lack of testing and the fact that it was not communicated properly.
 
### 3.3	Mitigating Software Vulnerabilities
It is always beneficial to tackle Software Vulnerabilities, as often, the vulnerabilities mentioned earlier can have an adverse impact on the security of the app or system. An attacker can exploit the system in many ways, which in turn leads to different purposes, such as data stealing or to damage a mainframe.

Modelling out the vulnerabilities is a good first approach to gain an understanding of what vulnerabilities can come out of development. By using the model as reference, it helps towards more careful development and can give the developer an idea on how to counteract said vulnerabilities. However, it would be considered necessary to count on methods to prevent the risks related to vulnerabilities.

Software Inspection is a method of vulnerability mitigation, in which its process is to read or visually inspect the program code or documents in order to find any defects and correct them early in the development process. This can help with the development as if they are found later, it becomes costlier to fix. Good inspection depends on the ability and expertise of the inspect, along with the defects in what he’s looking for [16].

Well embedded and upheld user access controls will restrict the applications, privileges and data that users can access, making for tighter controls to prevent sudden unauthorised access. Secure configuration can remove unnecessary software and default user accounts, making sure that passwords are changed and automatic features that could activate any malware to be turned off.

Monitoring software activity and analysing it to identify malicious or unusual activity, is a good call to help recognise a breach [17].

### 3.4	Conclusion
This conclusion ties with the case studies of both the Yahoo data breach and the NHS ransomware attack, it is revealed that the sole reason behind the attacks were down to the negligence of both organisations, where the difference lies in how the attack was brought on or handled. But in both cases on the matter to the cause of attacks, it is revealed that the attacks were caused because of outdated software, leaving an exploit open towards the attacker; where the case of Yahoo was because of outdated and easy-to-crack security tools that allowed the attacker to easily access Yahoo’ database, along with personal names, emails and hashed passwords, spanning over a devastating three billion users, and regarding the NHS case, an old unsupported operating system, Windows XP, was used as the main OS for all computers within the trust centre, lacking security controls currently implemented in more modern operating systems, having the attacker to exploit old tools and poorly embedded and maintained user controls to take control and access the files to encrypt.

Now, onto how each case was handled, both were handled poorly; the attack caused disruptions to the NHS centres and in turn had caused cancellation of appointments, leading to outrage amongst patients. Yahoo’s was more controversial, with them only issuing a disclosure of the breach three years later from the actual attack, the main issue being that the security team had the knowledge that the foundation was breached by a hacker, but failed to even try to enforce any prevention method. The NHS attack had sorted out in the end, despite the ongoing disruption to their workstations and systems, but the Yahoo breach had left all the accounts at risk and action taken was late. This dealing a massive blow to Yahoo.

Both were down to negligence and in my opinion on both matters, it seems that the issues were down to the lack of mitigation techniques. In the case of yahoo, the factors here where the outdated security tools, lack of analysis and lack of action, as it was clear that they knew the attack had been carried out, but only brought the breach to light at a later date. Had there been monitoring of user activity, finding any unusual activity would have meant that there was a breach and in turn would lead to quicker response. Updated tools would have also meant that the possibility of an exploit becoming apparent would be very unlikely.
In the case of the NHS, it would’ve been simple to impose the newest, modern operating system, containing tools that aren’t present in older operating systems. Forcing cyber security standards within every trust would also have proven beneficial as that can impose tighter security and better embedded access controls.

##### 3.5 References
1.	Software Development. [online]. Techopedia. Available from: <https://www.techopedia.com/definition/16431/software-development>. [Accessed 19 February 2018].
2.	Elysium Academy Private Limited (2017). What are the Software Development Life Cycle (SDLC) phases? [online]. LinkedIn. Available from: <https://www.linkedin.com/pulse/what-software-development-life-cycle-sdlc-phases-private-limited>. [Accessed 2 March 2018].
3.	Duncan Haughey (2014). REQUIREMENTS GATHERING 101. [online]. Project Smart. Available from: <https://www.projectsmart.co.uk/requirements-gathering.php>. [Accessed 02 March 2018].
4.	Tree Swing Project Management [online]. (n.d). Available from: <https://www.tamingdata.com/2010/07/08/the-project-management-tree-swing-cartoon-past-and-present/>. [Accessed 02 March 2018].
5.	Margaret Rouse, Matthew Haughn (2014). vulnerability. [online]. WhatIs.com. Available from: <http://whatis.techtarget.com/definition/vulnerability>. [Accessed 19 February 2018].
6.	SecureList [online]. (n.d). Available from: <https://securelist.com/threats/software-vulnerabilities/>. [Accessed 19 February 2018].
7.	Apple Developer [online]. (2016). Available from: <https://developer.apple.com/library/content/documentation/Security/Conceptual/SecureCodingGuide/Articles/TypesSecVuln.html>. [Accessed 19 February 2018].
8.	Inter Process Communication (IPC). [online]. Techopedia. Available from: <https://www.techopedia.com/definition/3818/inter-process-communication-ipc>. [Accessed 19 February 2018].
9.	OWASP (2016). Insecure Temporary File [online]. Available from: <https://www.owasp.org/index.php/Insecure_Temporary_File>. [Accessed 19 February 2018].
10.	Jonathan Stempel, Jim Finkle (2017). Yahoo says all three billion accounts hacked in 2013 data theft. [online]. Reuters. Available from: <https://www.reuters.com/article/us-yahoo-cyber/yahoo-says-all-three-billion-accounts-hacked-in-2013-data-theft-idUSKCN1C82O1>. [Accessed 20 February 2018].
11.	Vindu Goel, Nichole Perlroth (2016). Yahoo Says 1 Billion User Accounts Were Hacked. [online]. The New York Times. Available from: <https://www.nytimes.com/2016/12/14/technology/yahoo-hack.html>. [Accessed 26 February 2018].
12.	Michael Kan (2017). Yahoo execs botched its response to 2014 breach, investigation finds. [online]. CSO. Available from: <https://www.csoonline.com/article/3176181/security/yahoo-execs-botched-its-response-to-2014-breach-investigation-finds.html>. [Accessed 26 February 2018].
13.	NHS 'could have prevented' WannaCry ransomware attack (2017). [online]. BBC News. Available from: <http://www.bbc.co.uk/news/technology-41753022>. [Accessed 1 March 2018].
14.	Josh Fruhlinger (2017). What is WannaCry ransomware, how does it infect, and who was responsible? [online]. CSO. Available from: <https://www.csoonline.com/article/3227906/ransomware/what-is-wannacry-ransomware-how-does-it-infect-and-who-was-responsible.html>. [Accessed 1 March 2018].
15.	Support for Windows XP ended [online]. (2014). Available from: <https://www.microsoft.com/en-gb/windowsforbusiness/end-of-xp-support>. [Accessed 1 March 2018].
16.	Willy Jimenez , Amel Mammar and Ana Cavalli (2014). Software Vulnerabilities, Prevention and Detection Methods: A Review. Evry, France: ResearchGate. Available from: <https://www.researchgate.net/publication/253704494_Software_Vulnerabilities_Prevention_and_Detection_Methods_A_Review_1>. [Accessed 03 March 2018].
17.	Common cyber attacks: reducing the impact. (2016). National Cyber Security Centre. Available from: <https://www.ncsc.gov.uk/content/files/protected_files/guidance_files/common_cyber_attacks_ncsc.pdf>. [Accessed 03 March 2018].

## 4. Evaluation
### 4.1	Testing Report
### 4.2	Evaluation 
### 4.3	Critical Analysis
### 4.4	Future changes
