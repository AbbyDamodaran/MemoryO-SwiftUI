# Project 4 - *MemoryO*

Submitted by: **Abinaya Damodaran**

**MamoryO** is an app that allows you to play a classic memory game but with animal emoji cards!

Time spent: **2** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App loads to display a grid of cards initially placed face-down:
  - Upon launching the app, a grid of cards should be visible.
  - Cards are facedown to indicate the start of the game.
- [x] Users can tap cards to toggle their display between the back and the face: 
  - Tapping on a facedown card should flip it to reveal the front.
  - Tapping a second card that is not identical should flip both back down
- [x] When two matching cards are found, they both disappear from view:
  - Implement logic to check if two tapped cards match.
  - If they match, both cards should either disappear.
  - If they don't match, they should return to the facedown position.
- [x] User can reset the game and start a new game via a button:
  - Include a button that allows users to reset the game.
  - This button should shuffle the cards and reset any game-related state.
 
The following **optional** features are implemented:

- [ ] User can select number of pairs to play with (at least 2 unique values like 2 and 4).
  * (Hint: user Picker)
- [ ] App allows for user to scroll to see pairs out of view.
  * (Hint: Use a Scrollview)
- [x] Add any flavor you’d like to your UI with colored buttons or backgrounds, unique cards, etc. 
  * Enhance the visual appeal of the app with colored buttons, backgrounds, or unique card designs.
  * Consider using animations or transitions to make the user experience more engaging.

## Video Walkthrough

Here's a walkthrough of implemented user stories:


![W4 MemoryO Demo](https://github.com/AbbyDamodaran/MemoryO-SwiftUI/assets/78409617/b44dd8ae-39f8-4ccf-8a0e-4c721424e8e8)


## License

    Copyright [2024] [Abinaya Damodaran]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
