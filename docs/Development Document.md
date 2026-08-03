# Development Document

## Project

- Project name: Bracer Guild - Pom Party
- Course and assignment: Week 10: Game Development: Part 1 Documentation
- Developer or team: Kenneth Franco (Individual Project)
- Date started: 7/31/2026
- Technology or language: Visual Basic .Net WPF Project


## Brief

### Goal

I am building a game based on the Trails series which has a stacking Tetris inspired game of the same name but the more you stack
the more CP you build and in turn you can either clear your board or add more to your opponents board.

### User or player

Anyone will be able to play it since it is a simple game. They will understand the need to stack similar colors together and build their
power to either clear their board or add more to the opponents boards.

### Required deliverables

- [ ] Add each assignment requirement here.
- [ ] Mark starred or critical items.
- [ ] Record the submission destination.

Context and Game Study
Prepared Environment
Development Document
Adaptation Decisions
Prepared Assets
Readiness Review and Discord Proof
Git History *
Root README Map *
Complete Repository *
Accessible Git Link *



## Story or context

The Epstein Foundation developed Pom! Pom! Party! in order to build and test connections between the orbal net and see how to further develop a smoother connection.
With a simple ID number, players with their Enigma or at home computer can play in real time and not only help expanded the orbal internet but have a fun time as well.

## Product definition

Describe the smallest complete version you expect to build and test.

The smallest complete version I expect to build and test has a title screen with image assets and a simple tetris style gameplay as the base.
It will have the unique colored blocks and a way to delete and add more to the board instantly depending on how many blocks have been cleared
already.

## Reference study and adaptation

| What I noticed | Keep, change, or replace? | Why? | Update needed in my plan |
|---|---|---|---|
| Example: The tutorial begins with a title screen | Keep | The player needs a clear entry point | Add title screen to the screen map |

|The gameplay features a image asset as the background|Keep|It adds uniqueness and adds immersion|Find Image Asset to use as background for gameplay|
|The ball hits the bricks and they disappear off the board|Keep|I want something that is similar when stacking the same colors and having the bricks dissapear|Ensure bricks disappear when interacted with|
|Starts with "Title = MainWindow" and adjusts Width and Height|Keep|I want to be able to create a good sized window so that it doesn't feel clunky or tight|Add a tested window size that feels good to play on|
|Code for "DrawBricks"|Change|I want to make the bricks the main source of gameplay instead of relying on the ball|Find a way to allows bricks to fall and stay in place|

## Systems and screens

| System or screen | Input | Action | Output |
|---|---|---|---|
| Example: Main menu | Start button | Opens the game | Game screen appears |

|Main Menu|Start Button|Opens Game|Game Begins dropping Bricks
|Move Brick Left or Right|Left or Right Arrow|Moves Brick|Brick Moves to desired area
|Move Brick Down Faster|Down Arrow|Brick Moves Down|Allows Brick to fall faster
|Colors Match Row|Row Full of Color|Row Clears|Gain CP
|CP Meter|Enter Key|Auto Filling Gauge|Allows Ability to Remove from personal or add to opponent.
|Game Over|You or Opponet reach the top before the other|Ends Game|Restart or Exit Buttons Appear


## Information containers

| Variable, property, list, or table | Data type | Purpose | Example value |
|---|---|---|---|
| Example: playerHealth | Integer | Stores current health | 100 |

|CP Gauge|Integer|Shows CP Level|200
|Total Score|Integer|Shows Score of Each player|15000
|Current Brick|String|Shows Current Brick falling down|Blue
|Next Brick|String|Shows the Next Brick to fall after you place the current|Red
|Brick History|String|Shows previous number of bricks fallen down|Red, Green, Purple, Orange, Orange, Green, Blue, Yellow
|Speed|String|Allows to speed up or slow down gameplay|0.5x, 1.0x, 1.5x, 2.0x, 3.0x


## Actions

| Function, procedure, method, or event | Purpose | Input | Result |
|---|---|---|---|
| Example: CalculateDamage | Calculates attack damage | Attack power | Damage amount |

|MoveBrick|Moves Brick to Desired Location|Left or Right Arrow|Brick Moves
|PlaceBrickFast|Brick Falls Down Faster|Down Arrow|Brick Moves
|Game Speed|Allows faster or slower gameplay|Space Bar|Gameplay Speeds up
|Defense|Clears personal rows depending on CP used|Enter Key|Gives you more room
|Action|Adds Rows to opponents board|Enter Key|Gives opponent less room
|Surrender|Forfiet the match if their is no hope|F4|Surroender and give up the win
|RestartButton|Allows for Game to be played again|Mouse Click Button|Starts Game from beginning


## Environment

- Required editor: Visual Studio
- Required workload or SDK: VB.Net
- Project template: WPF Project Application
- Required packages or libraries: Base .Net Installation
- Operating system or device: Windows 11
- Proof that setup works: Game is functional and runs with no code errors.

## Assets

Link to the Asset Manifest and list the assets needed for the first working version.

Asset Manifest Located in GitHub Asset Folder

First Working Assets:
Background
Brick Models for all colors
Scoreboard
Game Over Screen
Title Screen
CP Icons for Attack and Defense
Unique Board Designs

## Milestones

| Milestone | Definition of done | Target date | Status |
|---|---|---|---|


|Project setup|Empty project runs and is committed|Week 10|Complete
|Development Document|Document typed with all accurate information|Week 10|Complete
|Adaptation Decisions|Document typed with all accurate information|Week 10|Complete
|Prepared Assets|Have Assets Ready to Use in Project|Week 10|Complete
|Complete Repository|All Submission Requirments met|Week 10|Complete
|Tested and Working First Build|Game Runs and has the general skeleton|Week 11|In Progress
|Final Game|Game complete with all assets and functionality|?|In Progress

## Questions and decisions

| Date | Question or problem | Source used | Decision or answer | Next action |
|---|---|---|---|---|

|8/1/2026|How should I create base title screen and project?|Retro Game Using VB.Net Tutorial Videos|Create as shown in video.|Ensure Functional
|8/1/2026|How can I ensure that the bricks will disspear when combined?|Retro Game Using VB.Net Tutorial Videos|Create as shown in video.|Ensure Stable
|8/2/2026|Is there anything specifc I need to have before building the first version?|Week 10 Website|Read and complete all submission requriements before week 11|Approach Week 11 with everything planned.


## Risks

List anything that could block the project, including missing tools, unclear requirements, asset permissions, difficult features, or time limits.

Assets not fitting gameplay as intended
Mistyped code that allows game not to run
Not reading requirements thoroughly and missing steps
Visual Studio not being setup properly.
Not following along slowly.
Asking colleagues for assistance with time in advanced.
Being to ambitious but not having a plan to set in motion.