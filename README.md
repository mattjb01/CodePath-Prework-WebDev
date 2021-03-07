# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Matthew Broadbent

Time spent: 3 hours spent in total

Link to project: (https://glitch.com/edit/#!/matthew-memory-game)

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
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![http://g.recordit.co/0uQ8IvDcpR.gif]
![http://g.recordit.co/VOs1SVBy95.gif]



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
No additional outside resources used.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
As someone who knows some music theory, I noticed that the given 4 given frequencies matched a dominant 7 chord. I wanted to change the frequencies to outline some other chord in the same key.
After adding two more buttons, I decided I would try for a half-diminished chord with an extra tonic and minor 10th on top. However, I soon realized that the frequencies of the notes with javascript do not scale linearly, as I tried to use math to figure out what they ought to be, with the assumption that they were linear.
In the end, I was able to use my ear to deduce the approximately correct frequencies.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
With web development, I am wondering how routing is done if you were to solely use HTML + CSS + JavsScript. I have only made actual web dev projects using frameworks or libraries like Django and React.JS, so I do not know how routing is done outside of the context of these tools.
It also seems that using plain HTML + CSS does not have as much reusability as you would get using a library or framework, so I wonder how you would deal with that.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours, I would increase the number of of elements in a pattern, so it is more difficult to win. However, if I were to do this, I would also need to reduce the rate that the game speeds up, or else it would end up too fast by the later turns.
I would also consider making it so that the player has to go through multiple patterns in order to win (maybe 3). Both of these features would make the game more difficult.



## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.