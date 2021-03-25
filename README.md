# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Yeabkal Biru**

Time spent: **3.5** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

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

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](http://g.recordit.co/IcfiU0atRu.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://www.w3schools.com/]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[Since I am currently working with Java, I found it rather difficult to get used to the syntax differences between Java and JavaScript and kept on getting a syntax error, but I got used to it quickly. It was also a bit tricky understanding the logic behind connecting JavaScript with HTML, but after I used external resources like that of W3Schools, most things became clear.
Following up with all the functions in the JavaScript file was also not very easy. Once I went through the code provided and understood everything, I found it easy to alter the provided code and add my functionalities to the game.
Even though it did not take as much, the other difficulty was adding more buttons to the game. It took me a couple of minutes of continuous debugging before I figured out that the new button numbers also have to be added to the pattern array to be accessed in the function “playClueSequence()”. In addition to using an external resource, I properly utilized the documentation provided to solve the issues.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[This project taught me a lot. I learned how to connect HTML, CSS, and JavaScript to create a static website. A question I have that I want to look into would be that if I want to make a multiplayer version of this game or any web-based game for that matter, how possibly can it be implemented?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had more time to work on this, there are certain things I would have liked to add. First of all, I would have added an input field to collect the name of the players. The game then keeps the score of each person so the high-scorer can be known.
A second fix would be instead of using the length of the pattern array to determine the duration of this game; I would have used a while loop with certain conditions inside of the playClueSequence function to let the player keep playing unless the game is lost.  
I also would have added a level of difficulty to the game. The player can pass to a higher level after winning each one. for this functionality, I would increase the “cluePauseTime” to decrease the pause time between clues to make the game harder after each level.]



## License

    Copyright [Yeabkal Biru]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.