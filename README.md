# Project 1 - Wordle

Submitted by: **Fariha Kha**

Wordle is an app that challenges players to guess a hidden 5-letter word within six attempts. With each guess, the app provides visual feedback indicating correct letters and positions.

Time spent: **3** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App displays a keyboard on the screen
- [x] When tapping on the keyboard, a letter is shown or deleted (letter selected)
- [x] User can play a basic version of Wordle, with different goal words each time
- [x] Correct letters are highlighted (yellow for correct letter, green for correct letter+position)
- [x] Incorrect letters are marked gray
- [x] Animations when letters are entered

The following **optional** features are implemented:

- [ ] Improve and customize the user interface by adding a launchscreen and app icon
- [ ] Run the app on a device rather than in the simulator

The following **additional** features are implemented:

- [x] Smooth animations when typing letters
- [x] Clean visual feedback for letter status
- [x] Random word generation from a predefined list

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://i.imgur.com/YOUR_LINK_HERE.gif' title='Video Walkthrough' width='300' alt='Video Walkthrough' />

[[Alternatively: Loom video link here](https://www.loom.com/share/d4b7c8b113c94d3c81d1749c2c636ea6?sid=5c330624-8c96-4b7c-8bff-45f1e43bfd08)]

## Notes

**Challenges encountered:**
1. Initially struggled with connecting the keyboard input to the board display
2. Had to debug the collection view cell animations to make them smooth
3. Implementing the color-coding logic for letter feedback required careful array manipulation

**Key Learnings:**
- Working with UICollectionViews and their delegates
- Implementing game logic in Swift
- Creating custom cell animations
- Managing state between different view controllers

## App Architecture

The app follows a simple MVC pattern:
- **Model**: `WordGenerator` handles word selection
- **View**: Storyboard with collection views
- **Controller**: `BoardController` and `KeyboardController` manage game logic

## License

    Copyright [2025] [Fariha Kha]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
