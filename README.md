# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **WEIMING CHEN**

Time spent: **More than 6** hours spent in total

Link to project: (https://github.com/chenwm99999/CodePath-Preword.git)

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [x] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] The game is more difficult, with seven tones forming the scale
- [x] The "Hint" button can prompt the user for the first note
- [x] Scales and sounds are random every time

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/WfmaBne8zX.gif)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[My roommate Kris Dong, my collegue from Baidu Inc Jiafeng Li]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[Honestly, the whole project was a huge challenge for me. Before today I would only use python and java (and extremely limited C language), and I only have experience in using python to complete projects, such as encapsulating databases and making modules. More over, I didn't learn about HTML, Javascript and CSS in university courses. Before starting this project, I spent a week teaching myself HTML and other related knowledge. Everything is difficult for me. For example, after I just learned the basic syntax of HTML, it is incomprehensible to me to use JS create function and modify the content of HTML by get ID. I asked my roommate about this. the process of learning all by myself is painful. Finally, after completing the basic content of the game, I asked my colleague JiaFeng Li, who I was working with as intern at Baidu, to help me read the entire code content. He made several optimization suggestions.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YMy biggest question about web development is how do these HTML, JS and CSS languages ​​​​work together? This question may seem silly, but what I want to know is something deeper. For example, in the process of finishing my project (this is noted in the code file), I used to use "style.backgroundColor = red" to change the button to a new color after clicking, and then use "style.backgroundColor = yellow" to modify the button back to its original color. At this point, no errors were reported during the execution of these codes. However, the functionality I set for these buttons is overridden in the CSS, the color style after "hover" and "active" cannot be realized. This results in that after each button changes color, the user cannot change the color again by placing the mouse over it and clicking it. So I solved the problem using ".onmouceover" and ".onmouceleave", instead of using "style.backgroundColor = somecolor". I looked up a lot of information, and the answer I finally got was "Aft er the page loads the Jquery code, the JQurey action trigger event overrides the css:hover action event". I'd love to know why this is the result.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I have enough time, I will add some interesting features. The first is mentioned in the options, I will increase the play interval function. Each time the difficulty increases, not only does the number of notes increase, but the interval between each note is also decreased. The second function is that I will make each button a piano key of varying length. Because my game contains 7 buttons which are "F G A B C D E". This makes the game interface more like a piano scale. The third function may be to add some game functions, such as the player needs to click the buttons in the reverse order.]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/461f5639d1b54a22abed158a60708d3a)


## License

    Copyright [WEIMING CHEN]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.