[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Matthew Murphy
### Student number: 47954450 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
During section 1 of the level the player discovers the staff locked behind a door that they must use to break the pillar blocking the key. When the player encounters the door they are required to make their way up each of the platforms above the staff so that the moveable block can be pushed onto the pressure pad to unlock the door. This encounter teaches the player the principals needed to unlock the gun later in the level, as when the player discovers the door blocking the gun they will already have been introduced to the mechanics required to unlock the door. However, these mechanics will vary from the mechanics introduced to the player before, as the platforms will now move allowing for the player to discover a new mechanic since they have progressed further through the level. This introduction of moving platforms allows for the player to be introduced to new mechanics by using their familiarity of mechanics from section 1 to create newly discovered mechanics that the level is able to build upon based on the players experiences from earlier sections in the level.

Section 1:

![Section1](DocImages/1.1_Discovery.png)

Gun example:

![Gun](DocImages/1.1_Discovery_2.png)


### 1.2. Drama
The intensity curve of the level fluctuates multiple times throughout the level with it changing based on the intensity of the interaction that the player has just faced, for example in section 1 after the player has cleared the area where they must jump over the spiked blocks while trying not to fall into the acid below them, the player is presented with a puzzle to solve afterward. This modulates the intensity of the level as the player goes from an area with a large amount of tension where they can fall into acid with a single wrong jump to an area where this tension is then relieved with a puzzle that does not put the player in a likely situation of death. By modulating the intensity of the level multiple times as the player progresses through it, it allows for the player to reflect on the tension and intensity that they have just experienced in the previous area before the tension and intensity of the level increases again when the player proceeds to the next area.

Tension to Relief:

![ToRelief](DocImages/1.2_Drama.png)

Relief back to Tension:

![ToTension](DocImages/1.2_Drama2.png)



### 1.3. Challenge
The level introduces different challenges to the player as they progress throughout the level as the player is introduced to each new mechanic individually before it is then combined with another mechanic to create a new layer of difficulty for the player. The final area of the level is a combination of all the different mechanics and challenges that the player has been introduced to throughout their time playing the level, this means that the difficulty curve of the level is gradual and that by the time the player reaches the final area of the level they are not overwhelmed by the increase in difficulty. This allows for the player to stay in a constant state of flow where as they progress through the level the difficulty of the challenges they face increase along with the each new mechanic introduced resulting in a gradual increase in difficulty that does not cause the flow to break. By controlling the flow of the level in this way the difficulty curve that the player experiences is never to extreme meaning that each challenge presented to the player feels unique and interesting.

New layer of difficulty added to existing mechanic:

![NewMechanic](DocImages/1.3_Challenge.png)

Combination of all mechanics introduced:

![Combination](DocImages/1.3_Challenge2.png)



### 1.4. Exploration
The player is encouraged to explore different spaces within the level through player curiosity, as the level has been designed so that the player is rewarded for investigating the different spaces that take their interest, these spaces are made distinct by being placed in ways to where the player can easily skip over them. These spaces are best demonstrated by the gun pickup at the end of section 2 and the health pickups at the start of section 3. As these spaces contain items that are valuable to the player, thus meaning that if players decides to ignore the space with these items the remaining sections of the level will become more difficult. Therefore, player curiosity encourages exploration of these different spaces as by choosing to explore these spaces the player is rewarded with valuable items that make the remaining sections of the level easier. By designing these spaces so that players are rewarded for their exploration distinct areas are created where the player is encouraged to investigate each of these spaces for the valuable rewards given in return.

Gun Pickup:

![Gun](DocImages/1.4_Exploration.png)

Health Pickup:

![Health](DocImages/1.4_Exploration2.png)



## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid

### 2.2. Checkpoints

### 2.3. Chompers

### 2.4. Health Pickups

### 2.5. Keys

### 2.6. Moving Platforms

### 2.7. Passthrough Platforms

### 2.8. Spikes

### 2.9. Spitters

### 2.10. Weapon Pickup (Gun)

### 2.11. Weapon Pickup (Staff)

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

## Generative AI Use Acknowledgement

N/A
