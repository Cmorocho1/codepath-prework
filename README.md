# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Christopher Morocho**

Time spent: **6** hours spent in total

Link to project: https://valuable-forested-flat.glitch.me
https://glitch.com/edit/#!/valuable-forested-flat

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add!
 them here:
 Start of program with basic requirements, shows the buttons lighting up, and the formatting all properly done. ![](https://i.imgur.com/TaWqxY7.gif)
 End of program with basic requirements. Shows the end of the game( when screen turns dark).
![](https://i.imgur.com/j0KRAcr.gif)

![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[I used no outside resources besides the ones already linked in the SITE prework step-by-step guide, such as w3Schools.com and the SITE step-by-step guide itself. ]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[A challenge I encountered in creating the submission was actually incorporating the syntax for javascript. I mainly code in python and a little bit of java so getting the syntax for the last step where we had to incorporate the game logic for the guesses was hard to code for me. The logic was clear thanks to the diagram and I intially knew I had to create if statements to test for the conditions but I just didn't know how to write it. I overcame this by writing pseudocode first, and then using the resources available to me such as w3schools to find the necessary syntax I needed to actually code it in Javascript. ]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[While this project was mainly independent, how team focused and group oriented is software development? What are the different roles assigned to a group and what type of software or resources do these type of people use? Also, how do software engineers know where to begin when starting a project? Thanks to the guide I knew where to begin but I think that if I was given just a blank template I would be very lost. How often is the console used in web development over an IDE or a terminal? What about in debugging? I found the console.log function to be very useful but I was wondering if there a better way to debug or test code.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[Due to time contraints and other responsibilites I was only able to manage to complete the basic requirements for the SITE pre-work project, but I was already tinkering with how to implement other features. For instance, in my code you can see a failed implementation for a random number generator that randomly generates numbers between 1-4 to be used as pattern sequence. I tried my best to implement it but was getting issues with reference types. I created a copy of the global pattern array and then used a for loop to switch each index with a random number, returned the array, and then called it in startGame(), but that didn't seem to work and instead seemed to crash my program (my guess, the project is unable to read the pattern array because the types are incompatable) I ran a console log to see if any values in my array were printing out and they were, so I was stuck and due to shortage of time, decided not to implement it. 
Nevertheless, I will not abandon this project and although the prework is due on the 1st of April, I will regualarly update my repository with improvements, so stay tuned for that! I will try my best to fix the issue with the random number function and then move on to incorporating more buttons into the program, as well as improving front end issues like style and color. ]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://drive.google.com/file/d/1-SBCjTiA4wbubZgXEhBFTjmRpVWgyUm3/view?usp=sharing)


## License

    Copyright [Christopher Morocho]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.