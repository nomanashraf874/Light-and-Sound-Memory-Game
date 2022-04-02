# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **NAME**

Time spent: **3** hours spent in total

Link to project: (site:https://foamy-blush-zucchini.glitch.me/
                  code:https://glitch.com/edit/#!/foamy-blush-zucchini)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [X] User has a limited amount of time to enter their guess on each turn


## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
### Failure:
![](https://i.imgur.com/4NtNvUU.gif)
### Completion:
![](https://i.imgur.com/Er05eHW.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://stackoverflow.com/
http://vaidehijoshi.github.io/blog/2015/01/06/the-final-countdown-using-javascripts-setinterval-plus-clearinterval-methods/

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
 The biggest challange I encounter was setting up the countdown timer that would give the player a set amount of time to execute the pattern before the round ends. The Timer should:
 1. Be Visible to Player
 2. Game ends when timer hits zero
 3. Timer restarts every round
For the first part I ran into a problem trying to created a dynamically changing html text. I tried many implementations but to my disapointment none of them worked. So, I took my search to the internet and stackoverflow and got hint toward using innerHTML(document.getElementById("demo").innerHTML = "value";). The second and third part is the main functionality behind the timer. At first i thought a countdown variable would do the trick but that conflicted with the timer reset .Turns out I had to create a complex logic circuit using set and clearInterval. Athough i understood the base use cases for the functions but when it came to implementaion i was at a loss. I was also calling the functions several times leading to conflict with the existing code and all types of bugs. Thankfully I found a blog pertaining to the structure of building a countdown using similar logic. After a painful round of debugging the countdown timer was finally

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
   "Every answer one finds leads to ten more questions." My experience mainly lies in IOS App development. Xcode is very freindly when it comes to frontend development due to the various funtionalities using storyboards and such. Leading to the question how dynamic can you be in Web Development on the frontend aspect without the conveniencey of a platform like Xcode. My question leans toward the difficulty level of said task because I have seen some beautiful, organized and complex web applications and from what i can see these implementaions would be quite difficult! I am looking forward to exploring and learning these concepts in  more depth.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
   I would try to make the webpage more user freindly. I have found that eventhough some webpages have better applications they donot do as well as their competitors simply because people give prefrence to a more visually appealing and organized website. This would require small but time consuming tweaks. I would start off by changing the color palet to make the website more vibrant. Then I would change the buttons and sounds into something more creative and original. The current ones are quite boring! As far as functionality goes i thing adding difficulty levels that vary on the number of patterns and speed they are given would create a competative aspect to the game. Overall giving it abetter look and adding more content should make the website more engaging.


## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/t5ZNOwQISYY)


## License

    Copyright Noman Ashraf

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
