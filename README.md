# Jet Set Willy 3: A New Beginning

![Logo](https://github.com/LBruni98/Jet-Set-Willy-3-The-Unofficial-Sequel-/blob/master/Jet%20Set%20Willy%203%20Logo.png)

All work Copyright ©2018 by Reboot Games

Written by Luke Bruni

## Table of Contents

```
1. Project Management
  1.1 Revisions
  1.2 General Aims
    1.2.1 Overview of the Project
    1.2.2 Main Project Aims
    1.2.3 Individual Aims
    1.2.4 Objectives
  1.3 Project Management Plan
    1.3.1 Overview
    1.3.2 Scope
    1.3.3 Resources
      1.3.3.1 Unity
      1.3.3.2 Firebase
      1.3.3.3 Internet Access
      1.3.3.4 Appropriate Computer
    1.3.4 Cost
  1.4 Project Schedule
  1.5 Risk Assessment
  1.6 Quality
  1.7 Communication
  1.8 Feasibility Report
    1.8.1 Technical Feasibility
    1.8.2 Market Feasibility
  1.9 Development Aims
    1.9.1 User Stories
    1.9.2 Movement
    1.9.3 Combat
    1.9.4 Collision
    1.9.5 Items
    1.9.6 Enemies
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
  3.4 Primary Research
    3.4.1 Introduction
    3.4.2 How well do people know software vulnerabilities and vulnerabilities in general?
    3.4.3 What can a programmer do to prevent and reduce software vulnerabilities?
    3.4.4 How do people apply security in their personal lives?
  3.5	Conclusion
    3.5.1 Primary Research Conclusion
      3.5.1.1 Reflection on the Value of Research
      3.5.1.2 Communicating Recommendations
    3.5.2 Secondary Research Conclusion
  3.6 References
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
|1.12   | Luke Bruni |22/03/2018 |Important information of the game added                |

### 1.2 General Aims
#### 1.2.1 Overview of the project
The game Jet Set Willy 3 is the first year capstone project for my course at West Herts College, as part of rebooting retro games. The game is meant to be an unofficial sequel to the game, rather than just either remastering or remaking it, so as to justify the reason for the newer mechanics and features that I plan to add to the game. The game will be a cross between modern and retro, with the gameplay being revitialised for the modern market. Personally, another reason behind this project is to bring back an old icon from the past and introduce him to modern gaming

#### 1.2.2 Main Project aims
The main objective of this project is to create a rebooted version/sequel of the game 'Jet Set Willy'. The aim is to create this game with more features and a revitalised gameplay style.

#### 1.2.3 Individual aims
* As explained in the project's overview, I will need to create movement that would be on par with today's platformers
* I will create a newer objective for the game as opposed to the older games
* I will create a coop multiplayer environment that allows other players to play the story with each other
* I will create a combat system for the game
* I will plan to have something presented on the 23rd March 2018

#### 1.2.4 Objectives
* Have a fluid movement similar to that of more modern platformers as opposed to the stiff, slow movement of the older games, which was because of limitations of the time. The movement will be quick and more responsive which should help the game gain popularity with the target audience and will be tested by participants to make sure it achieves this goal. If it is considered by the partciipants to be smooth, then the movement has been achieved. Will have this by 2nd March 2018.
* Devise the newer game objective to keep to the theme of the game. Money will be the newer objective and will have its own features, such as pickups, values and progression. Will have done by 14th February 2018 and will implement in game and test by 2nd March 2018.
* Create the multiplayer aspect of the game using Firebase, a database system by google that is compatible with Unity. I will test the game to see if the other players are visible and move in real time. Once the player functions work perfectly, then the goal is achieved.
* Create a combat system that will play a minor part in the game. The aim here is to not let it intefere too much with the original gameplay that is significant to the series. To test if the combat functions to what I want, I will test it in a playthrough. If the combat system doesn't make the player overpowered, then the objective is achieved. Will complete by 6th March 2018.
* Create a demo that details all the progress that I have done in the game and showcase it to the client. The game should have all the important aspects of the game covered in a scripted playthrough. This will be tested by running the game and picking off the appropriate aspects of the game which are presentatble. Once the demo has a suitable amount of presenatable gameplay, I am able to present it. Will have ready on 23rd March 2018.

### 1.3 Project Management Plan
#### 1.3.1 Overview
This part of the document specifies a plan for the development of the game and outlines the resources and schedule that will be included within development. It will be subject to change during the game's development. The plan is based on the objectives and aims in the previous section.

#### 1.3.2 Scope
The game is labelled to be a sequel and will have a newer style to keep the game looking refreshed and not the same visually. As part of the newer features, the feel of Jet Set Willy must remain and shouldn't deviate too far from the original game.

Jet Set Willy 3 will have a newer platforming mechanics, more towards a modern audience with fluid control and good responsiveness, rather than the old system, which made the game difficult in some places and often impossible to clear. This should bode well with the newer mechanics of the game such as the constant scrolling and the faster gameplay.

Combat will be included to provide some action to the game. The player can punch, perform some combos and probably do some finishing moves, though this won't be the main aspect of the game, as the features must not spoil too much of the original formula. Enemies will be tough and the player can be easily overwhelmed, so avoidance is key.

#### 1.3.3 Resources
The required resources are as followed:

##### 1.3.3.1 Unity
The game will be developed in unity, reasons being that I have past experience of using the engine and that it has features that can help me with developing the game.

##### 1.3.3.2 Firebase
Firebase will be used for the games multiplayer aspect, with features contained that are common with most game hosting servers. The players data will be stored on the firebase database and tools that allow for players to be a assigned a space in a game. Conveniently, Firebase can be used with Unity with it's own features for monitoring players and messaging. 

##### 1.3.3.3 Internet Access
Internet access will absolutely necessary because research will be carried out in this project; secondary research by reading articles and webpages and primary research with web serveys and such. This will also be used to keep track of analytics of players in multiplayer games and to test the multiplayer portion of the game, as well as eventual publishing of the game.

##### 1.3.3.4 Appropriate Computer
At least a decent computer must be used in order help with the development of the game. The computer must be matching the minimum requirements of the software that will be used during development and to make sure that it can run well without issues.

#### 1.3.4 Cost
The platform I am developing is for PC where it is free and requires no developing license whatsoever. Unity Pro which is the engine that will be used will come at £125 a month. Development of the project will take around three months so that will add up to £375. The version of Firebase that will be used is entirely free, containing the features that I need so there will be no upgrading.

The PC for home development will be my own system priced at the time at £789. A secondary PC for home development will also be used for writing up documentation or for backup, which costs £300.

The internet that will be used cost £45 a month which as mentioned earlier with the amount of time for development will cost £135 for three months.

I am planning to create my own assets for this game and in order to create them, I'll use Microsoft Paint that has already come on my computer as standard. Photoshop will still be used incase of touch ups to the art and the cost of that is £20 a month. Development takes place over three months so that will add up to £60.

The overall cost of this project will add up to £1,659.

|ID|Resource Description|Expenses/plan|Total|
|--|--------------------|--------|-----|
|1|Unity Pro|£125/m over 3 months|£375.00|
|2|Firebase|Free|£0.00|
|3|Primary Laptop|Fixed Price|£789.00|
|4|Secondary Laptop|Fixed Price|£300.00|
|5|Internet and broadband|£45/m over 3 months|£135.00|
|6|Developing on PC|Free|£0.00|
|7|Microsoft Paint|Free|£0.00|
|8|Photoshop|£20/m over 3 months|£60|
||||**£1,659**|

### 1.4	Project Schedule
![Gantt Chart](https://github.com/LBruni98/Jet-Set-Willy-3-The-Unofficial-Sequel-/blob/master/Gantt%20Chart.jpg)

#### 1.4.1 Milestones
* 31st January 2018 - Initial idea
* 19th February 2018 - Project Management Documentation
* 23rd February 2018 - Design Documentation
* 23rd March 2018 - Playable demo
* 28th March 2018 - Playable, finished game

### 1.5 Risk Assessment

| No. | Risk | Probability | Severity | Risk Effect | Contingency/Mitigation |
| --- | ---- | ----------- | -------- | ----------- | ---------------------- |
| 1   | Scope Creep | 40% | Moderate | Original objectives and ideas may gradually expand to the point where the project may take far longer or have a possibility of failure. Scope creep may happen because of poor understanding of the original project, changes within the market or even competing forces within a company. | To prevent the risk of scope creep, ideas will be set and seen that they are followed with no major change. Any minor change is allowed, but with careful consideration, so factors like timelines are reworked slightly or more time is given to allow for this change. This in turn should help prevent any extreme scope creep. |
| 2 | Hardware/software issues | 20% | Significant | Issues here maybe storage devices are missing, damaged or corrupt files, that hinder the project greatly because of important files becoming unavailable, having to start again from scratch. The PC or router would be damaged or flat out stop working, causing huge delays in the project until they are repaired or replaced. | Storage backups will be used in case of any failure to the storage devices mentioned in 1.5.1. There will also be backup storage of the backups in case of an extreme outcome of the risk. In regards to internet failure with the router being broken, again the backups will help should there be any cloud files that cannot be accessed and the research portion of the project will be carried out first as hopefully the development of the game doesn't require internet connection, even the multiplayer portion. As mentioned in 1.3.3, there are two computers, the software can be installed on both computers with the same license so should a computer break down, the other will be used in place so the project can continue. |
| 3 | Cost Management | 35% | Catastrophic | During the project, issues such as lack of software or, in an unlikely case, changing ISPs to help with the internet may interfere with the original budget and cashing out for features or software for the product, with the risk of the project going over budget and the project failing because of it. | In case of the cost going too high, an extra amount is kept until anything comes up. This amount accounts for about half of the original budget. Also, the aims were considered carefully based on what I could use and the purhcases were already made. |

### 1.6 Quality
At Reboot Games, it is compulsory to ensure that the project is up to its highest standard, meets the requirements stated and performs without flaws. Tests during the development of the code, will be made at the end of each iteration to ensure that they function accordingly to the requirements, even elaborate testing and surveys from avid gamers will be made in order to determine if the philoshopical aims and individual aims have been achieved. Communication and constant updates should inform the client about each change to the game during development, so any changes won't have too much of an effect on the game and keeps to the original requirements. A schedule will be devised to order the tasks and ensure smooth development is carried out, so the game reaches the deadline on time and no corner cutting is present. After deployement, updates will still be pushed out, but not as great as in the development phase, mainly focusing on bug fixes that may arise from deployment.

### 1.7 Communication
Being this is an individual project, communication won't be planned or arranged as if it were a fully-fledged group project. However, this won't be considered a major drawback, as I am allowed to communicate with other people who are working on their individual projects, mainly for the reason of supporting, help, tips for my own project or feedback. We can communicate within three days of the week when we're all available during the development and communication can stretch to social media, such as facebook or messenger, as well as phone calls. Communication will reach to all members at any time and not just going to the same person consecutively, but spacing out to others if I request them.

### 1.8	Feasibility Report
#### 1.8.1 Technical Feasibility
The deliverables are to address the development properly and to show the game's progress. The project timetable being set and deliverables will be delivered at the end of each development iteration, such as documentation, design, testing, etc. so development won't be too built up and left until the last minute. The project will use the Unity engine for development because of the features that it contains that would prove beneficial to the development of the game and other seperate features that are compaitible with Unity, such as firebase, database software from google that will aid in the multiplayer aspect of the game, this alluding to the ease of using Unity.

#### 1.8.2 Market Feasibility
The growth of more retro looking titles has grown exponentially and more or less the need of these types of games have been growing. These sorts of games follow more faster paced but older looking games, stuff that would've looked possible at the time but would be of modern gameplay and performance. Being that this game is a sequel, it will look more retro but not exactly like the older games and be more faster paced than the games before it because of the performance of modern machines. This in turn should put a foot in the door to the retro genre of games as said genre does perform very well and being a sequel of older games, it should draw more of an attention towards older fans of the game.

### 1.9	Development Aims
#### 1.9.1 Movement
1. As a user, I would want to move left and right
2. As a user, I want to move at a fast rate
3. As a user, I want to jump to get to ledges
4. As a user, I want to duck to avoid attacks
5. As a user, I want to control the character using a control setup

| User Story | Task Description                             | Points |Due Date|
| ---------- |--------------------------------------------- | ------ |--------|
| 1          | Have the character move left and right       |   1    |24/02|
| 2          | Assigning the character's movement speed     |   1    |25/02|
| 3          | Have the chcarcter jump                      |   1    |26/02|
| 4          | Have the character duck                      |   1    |28/02|
| 5          | Assign key binding for each action           |   2    |02/03|

#### 1.9.2 Combat
1. As a user, I would want the character to punch
2. As a user, I want the character to block incoming punches
3. As a user, I want the character to finish off the enemy
4. As a user, I want to count how many times I punch the enemy

| User Story | Task Description                             | Points |Due Date|
| ---------- |--------------------------------------------- | ------ |--------|
| 1          | Have the character punch and assign damage   |   2    |28/02|
| 2          | Have the character Block                     |   2    |01/03|
| 3          | Create finishers in combat                   |   3    |02/03|
| 4          | Combo counter for measuring the amount of punches                                |   2    |04/03|

#### 1.9.3 Collision
1. As a user, I would want the charcter to stay on the ground
2. As a user, I want the character to bump into the characters
3. As a user, I want the character to get hurt by the hazards
4. As a user, I want to know how much health I have

| User Story | Task Description                             | Points |Due Date|
| ---------- |--------------------------------------------- | ------ |--------|
| 1          | Create the charcter contact with the ground              |   2    |25/02|
| 2          | Create the player and enemy hitboxes to determine collision                                    |   2    |28/03|
| 3          | Create Hitboxes to the hazards that hurt the player                                   |   3    |01/03|
| 4          | Assign player Health                                       |   1    |01/03|

#### 1.9.4 Items
1. As a user, I would want there to be many items
2. As a user, I want to know how much money I have
3. As a user, I want the character to pick up the money

| User Story | Task Description                             | Points |Due Date|
| ---------- |--------------------------------------------- | ------ |--------|
| 1          | Make items functional (e.g. Picking up items progress the game)                           |   2    |01/03|
| 2          | Make the money counter and quota functional to help progress the game                     |   3    |02/03|
| 3          | Make the charcter interact with the items                                 |   1    |02/03|

#### 1.9.5 Enemies
1. As a user, I would want there to be patrolling enemies
2. As a user, I want to the enemy to know where I am
3. As a user, I want to know when the enemy gets knocked out

| User Story | Task Description                             | Points |Due Date|
| ---------- |--------------------------------------------- | ------ |--------|
| 1          | Create the pathing of the enemies            |   2    |25/02|
| 2          | Create a system that alerts the enemy to the player                         |   5    |01/03|
| 3          | Assign Enemy Health                                 |   3    |04/03|

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

### 3.4 Primary Research
#### 3.4.1 Introduction
In the wake of security breaches, it is revealed that likelihood of an attack is very high and the effects can be devastating to that of a company. To aid in the report, I have devised a survey to gather information on the awareness of vulnerabilities, knowledge and prevention of vulnerabilities and personal security, mainly to understand people’s stance and knowledge to security; how important it is, if they do understand the implications of the lack of security and how they can reduce the vulnerabilities that rise the chance of being attacked.

The survey was divided into three parts: Awareness, Software Security and Personal Security. This was mainly done to facilitate the survey and the question structure for this report. The first part is more of a mixture between quantitative and qualitative questions, mainly to back up what the user has answered in the first part of the question to actually see if their knowledge actually stands, helping out results further to the report. The second part of the report is more qualitative, requesting the user give more detailed answers to the questions so it helps understand what they know about software security, where just using quantitative questions wouldn’t gather as much in this regard. The third part of the survey is more along the lines of quantitative questioning as it helps give truly honest answers from users and doesn’t look like the questions are trying to expose the user. Qualitative questioning in this part would mean either untrue answers or answers that would be hard to draw a conclusion to.

A selection of 20 people was chosen to answer all selected at random from different parts of the IT department of the West Herts college. The reason behind this method of sampling is that the answers should vary from person to person and should result in some interesting results. The people who answered the surveys will not have their names recorded and all physical copies will be disposed of indefinitely after the results are written up to excel.

#### 3.4.2 How well do people know software vulnerabilities and vulnerabilities in general?

![Chart 1](https://github.com/LBruni98/Jet-Set-Willy-3-A-New-Beginning/blob/master/Images/Chart1.png)

For the first Question, it asked for the knowledge of software vulnerabilities. As the chart states, a majority of people were more along the lines of ‘average’ knowledge. Second best being ‘good’ knowledge, the main answer that should be expected of students working in the IT department, especially in regard to software development. The results were also taken from different departments, such as a business or others that wondered by, such as tutors, so their knowledge would be ‘poor’, however, what surprised me was the fact that no one answered ‘very poor’, meaning there was at least a low-level knowledge of software vulnerabilities.

Onto part b of the first question. This part was mainly used as a backup towards the first question, in which the reason behind was to verify if the person does indeed know what vulnerabilities are. Almost all answers were backed up clearly, but it’s interesting to note that the people that two people that answered ‘average’ and ‘good’ did not back up their question and instead either wrote ‘nothing’ in the box or didn’t write anything at all. This could mean many things, commonly though, it could mean that they actually have no idea or simply forgot.

![Chart 2](https://github.com/LBruni98/Jet-Set-Willy-3-A-New-Beginning/blob/master/Images/Chart2.png)

The second question has the same format but asks on the types of vulnerabilities that they know off, rather than vulnerabilities in software. The expected result would be that at least a low-level amount of knowledge of viruses regardless, where certain participants did answer with a ‘good’ despite their answer in the first question of this part. However, it also happened vice versa (answered ‘poor’ or ‘very poor’) with a couple of participants, which is surprising considering that their results in the last question have been answered with ‘good’. This could mean anything.

Part b of this question is similar to the results in the first question, where answers backed up their knowledge. It’s important to note that those who answered with ‘Excellent’ gave more in-depth answers with examples to showcase their knowledge. This was the same as in the first question of this section, where those who answered ‘Excellent’ were sure to give answers that were different to those who answered ‘Good’ or ‘Average’ in the first part.

#### 3.4.3 What can a programmer do to prevent and reduce software vulnerabilities?
The next part of the survey was more of written answers and is the perfect basis for this question.

The first question was in software vulnerabilities, ‘How do you reduce vulnerabilities?’. All had answered with what would be commonly used to reduce vulnerabilities so at least a level of understanding is present with how they can reduce vulnerabilities. The quality in answers varies between departments, with those in business or other departments answering with ‘Install Anti-virus software’ or obvious answers along the lines. Those in software development departments answered more in depth, with ‘checking code’ or ‘software analysis’.

The second question revolves around areas of mitigation, ‘What sort of methods would make for good mitigation?’. This question revolves around what sort of methods would the developer take in case an attack should happen. Unfortunately, a majority of answers show that some people didn’t understand the question whatsoever, answering with nothing; common from those in departments other than software development, or answering with the same from the first question; common here from development departments. Only a couple of participants answered with proper mitigation techniques, so if the wording of the question being hard to understand may be up for debate.

The third question, ‘What are the issues of a vulnerable piece of software?’, goes into what consequences may arise if the software is not secure or developed well. As usual, the software development students and those who had good knowledge based on the first part gave pretty in depth and clear answers, but what is surprising is that some participants in business or other sectors gave good and relative answers that would be answered by those in software development, meaning that it could be picked up. Others in business or other sectors, were indifferent or just didn’t answer.

#### 3.4.4 How do people apply security in their personal lives?
The final part of the survey, investigates how secure people are in their personal lives and if they can apply it to their lives.

![Chart 3](https://github.com/LBruni98/Jet-Set-Willy-3-A-New-Beginning/blob/master/Images/Chart3.png)

The first question asks if the participants go on social media. The chart above shows that all but one participant answered with ‘yes’, showing that they remain social online. The reason can vary for the one person who doesn’t go on social media, but in relation to the survey could be information sharing.

![Chart 4](https://github.com/LBruni98/Jet-Set-Willy-3-A-New-Beginning/blob/master/Images/Chart4.png)

The next question asks how much personal information is shared online. The pie chart above shows that the majority of answers are ‘only a few’ and ‘Some of it’, these answers being that the only information given out is personal information to that of banks or login information. Only one answered ‘not at all’ so chances are that no personal information was given and no one said ‘all of it’, which went to what I expected.

![Chart 5](https://github.com/LBruni98/Jet-Set-Willy-3-A-New-Beginning/blob/master/Images/Chart5.png)

The next question goes into if one or multiple emails are used for all uses, this being personal or business, etc. The majority of people said no, indicating that more than one email is used for various purposes. Some people did say ‘yes’, meaning they might be unaware of the risks associated to having only one email for all purposes.

![Chart 6](https://github.com/LBruni98/Jet-Set-Willy-3-A-New-Beginning/blob/master/Images/Chart6.png)

The fourth question goes into the number of passwords used when logging in to various sites. The reason for this question is because of the risks accompanying having only one password and to understand if the participants know this risk. The chart shows that half of participants had voted to having ‘4+’ passwords, meaning that they understand the risks given to having minimal. What is important to note is that all participants have more than one password.

![Chart 7](https://github.com/LBruni98/Jet-Set-Willy-3-A-New-Beginning/blob/master/Images/Chart7.png)

The fifth question revolves around which password is harder to crack. Unlike the rest of the survey, this is the only question that has a correct answer. Both passwords were written out and tested on its amount of time to crack by using the site https://howsecureismypassword.net, a site that safely checks the password and based on the computer, returns the amount of time it would take to crack it. The password ‘SomeInfuriatingOverworkedCars’ takes substantially more time to crack than ‘In54N3b0sS’ because of how the structure of the password.

The majority of people come to the conclusion, based on the bar chart, that ‘In54N3b0sS’ takes longer to crack than ‘SomeInfuriatingOverworkedCars’ because of the assumption of the numbers and the randomly cased letter would make for a reinforced password.

The next question is ‘Do you regularly install updates?’. The importance here being that installing updates makes for an up to date and secure version of the software. All 20 of the participants had answered ‘yes’. This cancels out the reason for a chart.

![Chart 8](https://github.com/LBruni98/Jet-Set-Willy-3-A-New-Beginning/blob/master/Images/Chart8.png)

The final question tests the participant on their knowledge of phishing emails; emails that coax the user to giving valuable information to scammers. This question is set the same way as the questions in the first part of the survey with a second question that serves to back up the participant on their knowledge.

The chart above shows that the majority voted yes and in the second part of the question, gave sufficient factors of phishing links such as links in the email or poorly worded email addresses. Only one participant who answered ‘yes’ didn’t respond in the second part of the question.

### 3.5	Conclusion
#### 3.5.1 Primary Research Conclusion
The results of the survey confirm numerous things; the answers to the main questions and how well people understand vulnerabilities. It is revealed that the results confirm that there are a majority of people that understand software vulnerabilities, security and what makes for secure software, but the questions have just barely been answered due to the fact that some of the questions in the survey were answered barely.

The first question reveals that people have an average understanding of software vulnerabilities and vulnerabilities in general. From the results of the first part of the survey reveal that the majority have answered both parts and most does back up their knowledge. Those who claim to have answered well and didn’t back up their answer show that they don’t actually understand vulnerabilities in software or in general.
The second main question shows that they only understand how to ensure that software security and what the risks associated with unsecure software can bring, rather than actually understand prevention methods to do in case of any attack. The results show that only a few can show what methods of prevention that a developer would carry out.
The third question answers the question of how they can apply security in their lives. The survey shows that the vast majority of participants take measures to ensure security and understand what sort of malicious stuff can arise, showing us that they are more than capable of applying security safely.

##### 3.5.1.1 Reflection on the Value of Research
The primary research overall was more or less a success, as it did answer the questions that was the basis for this research. All twenty people managed to answer almost all of the survey with little to no trouble and has proved to provide a good amount of information that helped with answering the questions and assisting with recommendations. With the way I conducted the research, I managed to get the most honest answers that supported this report. The research was conducted with 20 people in the IT section of West Herts College, differing in branch and what was taught, such as business or software development, with emphasis on random sampling, giving us accurate and authentic results. Had the researched been structured differently, such as changing the sampling method or the people involved, then less than satisfactory results would be produced, making it harder to come to a complete verdict or result in biased answers.

As part of an in-depth view, I had structured the survey the way with random sampling so the people I chose had an equal chance of being selected. I thought that in a way, more random answers would be present and all would vary on person to person, this way it could help facilitate to more honest answers and would help me make better recommendations. In my opinion, if I were to use other sampling methods, such as Judgement or convenience sampling, then chances are that the result of answers would’ve been mostly biased or not clear cut. However, I find that the Random Sampling method does have its problems, moreover the risk of sampling error which is prominent with this method of sampling. If I had gone for a sampling method such as Systematic or Stratified, the answers I would have gotten would be more accurate and in turn the participants would’ve answered all of the questions on the survey rather than some give nothing or little for an answer.

Other points would be the format of the survey, the survey was divided in segments, which were done to help with analysing the data and setting recommendations. The issues were in the sense of how the questions were structured, with most surveys returned with a prominent question left unanswered, meaning that the question was presented in a way that was too confusing or specific. Even so that some did answer that question accordingly, the presentation of that question should have been changed. However, despite this, I found that the mix of written and selection questions help with gathering accurate data, especially in certain questions. If the whole survey were in tick box format, then only quantitative data would be present and wouldn’t be completely accurate and if the survey was mainly written, any participant wouldn’t be bothered to answer in full and if they were, it would be time consuming and not being beneficial toward both the surveyor or participant.

This survey, overall, provided me with the experience for gathering data and hopefully would be beneficial in the future. The survey has helped gather essential information regarding software vulnerabilities and in turn, helped with defining what should be done to reduce software vulnerabilities and reinforce security in software. Any positive and negative outcomes from this research will be noted and used for improvements.

##### 3.5.1.2 Communicating Recommendations
In response to the first question, it is important to understand the implications of software vulnerabilities as well as vulnerabilities in general, but given the results, I would say, in my opinion, that the knowledge presented was lacking from the following groups, both those involved in software development and business, despite their lack of utilising software. I would recommend that this knowledge is more enforced in both groups, educating software developers a more in depth view of software vulnerabilities and this would help considerably when it comes actually develop software, thus effectively apply their knowledge and techniques. With the other groups, at the least should have the knowledge of viruses and general vulnerabilities. The reason I’m recommending this is because viruses are a persistent threat in both normal and work lives. By learning this, they can easily recognize viruses and the threats associated with it, such as virus links in emails, etc.

My second recommendation mainly aims towards the group who are mainly involved in software development or similar. Those part of that group should gain more knowledge of software vulnerabilities, to pick up more on the foundations of said vulnerabilities, including methods of mitigation and security in software, also to be able to apply these secure methods when developing software. This in turn should help them understand software vulnerabilities and how to counteract them.

In regards to personal security, the answers from the survey generally showcase that in most cases, they understand the risks involved and do act on it (i.e. more than one email for different uses), leading to very interesting answers. I will still recommend that this knowledge of personal security still be enforced so people will improve on browsing the internet safely and other personal measures. This will also help with those who don’t normally use these measures when doing stuff online.

#### 3.5.2 Secondary Research Conclusion
This conclusion ties with the case studies of both the Yahoo data breach and the NHS ransomware attack, it is revealed that the sole reason behind the attacks were down to the negligence of both organisations, where the difference lies in how the attack was brought on or handled. But in both cases on the matter to the cause of attacks, it is revealed that the attacks were caused because of outdated software, leaving an exploit open towards the attacker; where the case of Yahoo was because of outdated and easy-to-crack security tools that allowed the attacker to easily access Yahoo’ database, along with personal names, emails and hashed passwords, spanning over a devastating three billion users, and regarding the NHS case, an old unsupported operating system, Windows XP, was used as the main OS for all computers within the trust centre, lacking security controls currently implemented in more modern operating systems, having the attacker to exploit old tools and poorly embedded and maintained user controls to take control and access the files to encrypt.

Now, onto how each case was handled, both were handled poorly; the attack caused disruptions to the NHS centres and in turn had caused cancellation of appointments, leading to outrage amongst patients. Yahoo’s was more controversial, with them only issuing a disclosure of the breach three years later from the actual attack, the main issue being that the security team had the knowledge that the foundation was breached by a hacker, but failed to even try to enforce any prevention method. The NHS attack had sorted out in the end, despite the ongoing disruption to their workstations and systems, but the Yahoo breach had left all the accounts at risk and action taken was late. This dealing a massive blow to Yahoo.

Both were down to negligence and in my opinion on both matters, it seems that the issues were down to the lack of mitigation techniques. In the case of yahoo, the factors here where the outdated security tools, lack of analysis and lack of action, as it was clear that they knew the attack had been carried out, but only brought the breach to light at a later date. Had there been monitoring of user activity, finding any unusual activity would have meant that there was a breach and in turn would lead to quicker response. Updated tools would have also meant that the possibility of an exploit becoming apparent would be very unlikely.
In the case of the NHS, it would’ve been simple to impose the newest, modern operating system, containing tools that aren’t present in older operating systems. Forcing cyber security standards within every trust would also have proven beneficial as that can impose tighter security and better embedded access controls.

##### 3.6 References
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
