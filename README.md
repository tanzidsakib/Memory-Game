# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Tanzid Sakib

Time spent: **5** hours spent in total

Link to project: (https://glitch.com/edit/#!/pre-work-memory-game)

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](http://g.recordit.co/LauhsUf5Ac.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 


None.


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 


I wanted to change the shape and size of each of the game button. I knew where to look but I was struggling to figure out which way it moves. Although it says width and height, if you increase or decrease by too much it becomes a drastic change. After playing around with it for a while I finally figured out how I wanted my game buttons to be and what pixels for width and height would satisfy me. I was also playing around with the frequency and the hold and pause times for a bit because the beeps would often get annoying if you are playing the game over and over again. I messed around with frequency of the sound because the higher toned beeps is not the best for the years. A screech doesn't sound too appealing for a memory game. I played around with the frequency for each game button and settled on the frequencies I thought would be the best for the game and the users. I changed the time for how long the clue holds because as well as the frequency of the sound, if the hold of the clue is too long its very frustrating. If the user is a couple clues in, hearing the clues for just as long is not very ideal. I also shortened the time in between the pauses of the clues to help the game run smoother and faster for the user. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 


Some questions about web development that came up while I was doing this project were how much time does a web developer put into thinking of the layout for the UI. I know coming up with different designs for some websites it didn't take much time for some web developers but for some it took a lot. I was wondering what are some websites that took a while coming up with their own UI, compared to what are some companies that came out with the UI for their website or apps in a very small time frame. I want to dig deeper and get a walk through of a professional web developers thoughts and what really they think about when designing and brainstorming such UI's.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 


If I had a few more hours to work on this project, I would've added a couple more things. I for sure would have put a constraint on how many mistakes you can have, such as give them 3 chances and if they mess up 3 times the game would be over. I also would've levels to the game. If level 1 is completing the game within 3 chances, level 2 would have had an added timer where if the game is not completed within a certain time frame, the player losses (the chances would still be the same). Level 3 I would have the playback of the sound to be faster and a time frame together. That would be the final level of the game, where if the user can complete each level they will fully finish the game. 

## License

    Copyright [Tanzid Sakib]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.