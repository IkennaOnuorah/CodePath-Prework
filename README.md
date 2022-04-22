# Pre-work - *Lights and Tunes Memory Game*

**Lights and Tunes** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ikenna Onuorah**

Time spent: **4** hours spent in total

Link to project: (https://glitch.com/edit/#!/light-sound-memory-game1234)

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
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
- I included a footer with my name and email at the bottom of the webpage

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

GameWin
![GameWin](https://cdn.glitch.global/9a43848f-29c5-4d08-86a7-5ecc82c1cb26/gamewin.gif?v=1650606107557)
GameLose
![GameLose](https://cdn.glitch.global/9a43848f-29c5-4d08-86a7-5ecc82c1cb26/gamelose.gif?v=1650605685328)
Fifth Button
![Fifth Button](https://cdn.glitch.global/9a43848f-29c5-4d08-86a7-5ecc82c1cb26/fifthbtn.gif?v=1650606443518)
Button Hidden Images
![Button Hidden Images](https://cdn.glitch.global/9a43848f-29c5-4d08-86a7-5ecc82c1cb26/btnhiddenimg.gif?v=1650606544004)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
    
    People:Andre Limos
    Websites: https://stackoverflow.com/questions/8683528/embed-image-in-a-button-element

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    There were a couple of things that I found challenging with submitting this prework. Part of it has to do with being fairly new to HTML, JS, and CSS. For me, it was the javascript file which I believe is the backend of my program. I would have trouble figuring out what was wrong with a function that had an error within it. It would sometimes make my buttons stop working by it not flashing the way it was intended or the sound didn’t play when a button was pressed. The one function that I spent the most time on was the guess function. The error I had with that function was on the third round of the memory game no matter what button was pressed even if it was the correct one the player would lose the game. I was able to fix this by adding my progress variable to my StartGame function. I didn’t really grasp the concept of HTML until I spent more time on it and following the steps from the prework instructions. It was a bit difficult for me to add additional aspects to my game that weren’t required since I’m new to creating web pages. So I had to use outside resources like stack overflow to find bits of code that would be adequate for my program. I added two extra features to make my game more interactive. I added an extra button, a footer with my info, and images that would appear when a button was pressed. I would then continuously test my webpage to confirm that everything was running properly.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

    What would be the hardest aspect of developing something regarding web development? Another one I had was what coding languages does a person need to know to make a great web developer? What are the best programming languages to learn to become a web developer? What are essential skills every web developer should have or know?


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    If I had more time to work on this project I would add features that would allow you to play against your friends or players online. After each game, I would want to implement a way to show the highest score for that round and for the game to update the score when the highest score is beaten. I would also want to implement a secret pattern that would lead to different sounds of each button after the secret pattern was inputted correctly. The main thing that I would want to implement is to give the player options. For example, letting the player choose how many tries he or she gets before losing the game. Also giving the player the ability to choose how many buttonshe or she would want to have during the game.




## Interview Recording URL Link

[My 5-minute Interview Recording](https://cdn.glitch.global/9a43848f-29c5-4d08-86a7-5ecc82c1cb26/video1973764121.mp4?v=1650609075639)


## License

    Copyright [Ikenna Onuorah]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.