# Introduction
- The purpose of this page is to create a space that helps me structure my fitness routine and improve my workout sessions.
- An Engineer's Approach to working out

## :ledger: Index

- [About](#beginner-about)
- [Motivation](#zap-usage)
- [Routine](#wrench-development)
- [Equipment](#wrench-development)
- [Workout](#wrench-workout)
  - [Pre-Requisites](#notebook-pre-requisites)
  - [Developmen Environment](#nut_and_bolt-development-environment)
  - [File Structure](#file_folder-file-structure)
  - [Build](#hammer-build)  
  - [Deployment](#rocket-deployment)  
- [Community](#cherry_blossom-community)
  - [Contribution](#fire-contribution)
  - [Branches](#cactus-branches)
  - [Guideline](#exclamation-guideline)  
- [FAQ](#question-faq)
- [Resources](#page_facing_up-resources)
- [Gallery](#camera-gallery)
- [Credit/Acknowledgment](#star2-creditacknowledgment)
- [License](#lock-license)

##  :beginner: About
Quick disclaimer: I am not a personal trainer 
But with so much information on working out, I found it overwhelming to understand what I wanted to get out of working out and what exercises matters to me. 

## :zap: Why working out? 
I think the first important step I took was asking myself why I wanted to work out and I came up with the following: 
- Run Faster & Jump Higher to be able to make cool plays in Ultimate Frisbee
- Build strength to prevent injuries
- Build good health habits before I reach old age
- 
By laying out my motivations, it helped me identify what the reasons were for working out and establish the overall big picture that would lead to my workout routine

##  :wrench: Routine
The next step I took was to identify how working out was going to fit into my life. How often was I determined to work out for? Where would I fit it in my calendar? I found it helpful to establish a weekly routine: 

| Day       | Activity        |
|-----------|------------------|
| Monday    | Upper Body                  |
| Tuesday   | Frisbee / Cardio                 |
| Wednesday | Abs                 |
| Thursday  | Lower Body                 |
| Friday    | Recovery Day                 |
| Saturday  | Frisbee / Cardio                 |
| Sunday    | Floater                 |

I think it's okay to deviate from the plan if life moments happen but establishing this routine gave me a general idea of how often I was willing to dedicate to working out. What also helped was adding a "Floater" Day in case I needed to shift my week due to an event. 

##  :wrench: Equipment
Next step was understanding what workout equipment I had available: Home equipment? Gym? Free weights? 
I decided to get a gym membership close to my work so I could go there after work and avoid the post-work traffic. 

##  :wrench: Workout
Once I established my time and equipment, I wanted to understand how I would structure my workouts. I decided to set two gym days: 1 for Upper Body and 1 for Lower Body. Then the Abs and Cardio days I can do at home or outside the gym. 

### :notebook: Upper Body
Based on what I've found, a good upper body workout involves working the following muscle groups
-  Chest: 2 exercises
-  Back: 2 exercises
-  Shoulders: 1 exercise
-  Biceps: 1 exercise
-  Triceps: 1 exercise

###  :nut_and_bolt: Lower Body
-  Quads: 1-2 exercises
-  Hamstrings: 1-2 exercises
-  Glutes: 0-1 exercise
-  Calves: 1-2 exercises

###  :file_folder: File Structure
Add a file structure here with the basic details about files, below is an example.

```
.
├── assets
│   ├── css
│   │   ├── index-ui.css
│   │   └── rate-ui.css
│   ├── images
│   │   ├── icons
│   │   │   ├── shrink-button.png
│   │   │   └── umbrella.png
│   │   ├── logo_144.png
│   │   └── Untitled-1.psd
│   └── javascript
│       ├── index.js
│       └── rate.js
├── CNAME
├── index.html
├── rate.html
└── README.md
```

| No | File Name | Details 
|----|------------|-------|
| 1  | index | Entry point

###  :hammer: Build
Write the build Instruction here.

### :rocket: Deployment
Write the deployment instruction here.

## :cherry_blossom: Favorite Templates

Upper Body
Warm Up: 
-  Lateral Band
-  Roll Out with Foam Roller
-  Dynamic Stretching on Pull-Up bar

| Muscle Group | Primary Activity | Secondary Activities |
|----------    |----------|----------|
| Chest #1     | Bench Press   | Dumbbell Press   |
| Chest #2     | Data 1   | Push-Ups   |
| Back #1      | Barbell Row   | Pull Ups   |
| Back #1      | Single Arm Dumbbell Row  | Data 2   |
| Shoulder #1  | Seated Dumbbell Press   | Data 2   |
| Biceps #1    | Dumbell Curls   | Data 2   |
| Triceps #1   | Overhead Dumbbell Tricep Extension   | Data 2   |

Lower Body
Warm Up: 
-  Lateral Band
-  Roll Out with Foam Roller
-  Dynamic Stretching

| Muscle Group | Primary Activity | Secondary Activities |
|----------    |----------|----------|
| Chest #1     | Bench Press   | Dumbbell Press   |
| Chest #2     | Data 1   | Push-Ups   |
| Back #1      | Barbell Row   | Pull Ups   |
| Back #1      | Single Arm Dumbbell Row  | Data 2   |
| Shoulder #1  | Seated Dumbbell Press   | Data 2   |
| Biceps #1    | Dumbell Curls   | Data 2   |
| Triceps #1   | Overhead Dumbbell Tricep Extension   | Data 2   |

 ###  :fire: Contribution

 Your contributions are always welcome and appreciated. Following are the things you can do to contribute to this project.

 1. **Report a bug** <br>
 If you think you have encountered a bug, and I should know about it, feel free to report it [here]() and I will take care of it.

 2. **Request a feature** <br>
 You can also request for a feature [here](), and if it will viable, it will be picked for development.  

 3. **Create a pull request** <br>
 It can't get better then this, your pull request will be appreciated by the community. You can get started by picking up any open issues from [here]() and make a pull request.

 > If you are new to open-source, make sure to check read more about it [here](https://www.digitalocean.com/community/tutorial_series/an-introduction-to-open-source) and learn more about creating a pull request [here](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github).


 ### :cactus: Branches

 I use an agile continuous integration methodology, so the version is frequently updated and development is really fast.

1. **`stage`** is the development branch.

2. **`master`** is the production branch.

3. No other permanent branches should be created in the main repository, you can create feature branches but they should get merged with the master.

**Steps to work with feature branch**

1. To start working on a new feature, create a new branch prefixed with `feat` and followed by feature name. (ie. `feat-FEATURE-NAME`)
2. Once you are done with your changes, you can raise PR.

**Steps to create a pull request**

1. Make a PR to `stage` branch.
2. Comply with the best practices and guidelines e.g. where the PR concerns visual elements it should have an image showing the effect.
3. It must pass all continuous integration checks and get positive reviews.

After this, changes will be merged.


### :exclamation: Guideline
coding guidelines or other things you want people to follow should follow.


## :question: FAQ
You can optionally add a FAQ section about the project.

##  :page_facing_up: Resources
Add important resources here

##  :camera: Gallery
Pictures of your project.

## :star2: Credit/Acknowledgment
Credit the authors here.

##  :lock: License
Add a license here, or a link to it.
