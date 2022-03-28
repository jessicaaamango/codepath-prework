# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Jessica Benitez**

Time spent: **10** hours spent in total

Link to project: https://glitch.com/~sound-and-memory-game

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
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

Game without additional features: ![Sound Memory Game](https://user-images.githubusercontent.com/101780073/159099285-3f0c81dd-4c86-4b37-afe3-42b4b094e1b6.gif)
Game with additonal features: ![Sound Memory Game Part2](https://user-images.githubusercontent.com/101780073/160022700-1f0744d2-5a1e-42d1-a94d-1a6ec4a85ac6.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

 - https://www.w3schools.com/cssref/css_colors.asp
 - https://stackoverflow.com/questions/39200994/how-to-play-a-specific-frequency-with-javascript
 - https://www.w3schools.com/js/js_if_else.asp
 - https://www.studytonight.com/css-howtos/how-to-add-a-button-to-an-image-with-css

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

While working on this project, I encountered many challenges. First, I struggled with putting the sesame street images on the button. The name of the image and a tiny image box kept showing up above or next to the buttons rather than on the actual button. I was able to overcome this once I realized it was the <img> on the HTML file that was causing this. I took it out and just put the link to the image from the assets into the actual CSS file. Secondly, I wanted to add the sesame street character songs onto the button. Unfortunately, I was unable to edit the clips down in the JS file itself since it kept playing the full length of the audio. Third, I tried to add the .random element but kept running into issues when trying to add each random number into a list of 8 components. The .random also kept trying to give back one value. Lastly, I struggled with adding a timer in when the player would attempt the level. I tried searching online for functions that would help but ended up not adding that feature altogether. I only seemed to have trouble with the additional features and not the original project itself.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing this project, I wonder if the next web projects will be anything similar to this one? This was my first time creating a game and I had a lot of fun working on this. Will we be working in teams in the future or will everything be an individual assignment? Also, how should I go about finding the solutions to add-on features that I have for future projects? For this one I just looked it up online but, I wonder if I will have anyone to ask for help when I'm struggling and can't find any more answers on google.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time to work on this project, I would spend them adding the additional features I had trouble adding. I feel as though my project would've been more unique if I was able to add the audios and .random function. I would also try reworking the frequency functions in order to turn them into audio snippet functions. It would be nice to also add different stages in the game. For example, when the player completes an entire pattern, they will be able to play a different pattern without hitting stop and move onto stage 2 of the game. I may continue to work on this project on my own in the future to see what else  I can add.


## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/Ym5HxNJ-pUM)


## License

    Copyright Jessica Benitez

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
