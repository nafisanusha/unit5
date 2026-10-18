# Project 5 - *Trivia Challenge*

Submitted by: **Nafisa Nusha**

**Trivia Challenge** is an app that lets users customize and play trivia games using questions from the Open Trivia Database. Players choose their question count, category, difficulty, and question type, then select answers and submit them to see their score. An optional timed mode adds a countdown and automatically submits answers when time expires.

Time spent: **1** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App launches to an Options screen where user can modify the types of questions presented when the game starts. Users should be able to choose:
  - [x] Number of questions
  - [x] Category of questions
  - [x] Difficulty of questions
  - [x] Type of questions (Multiple Choice or True False)
- [x] User can tap a button to start trivia game, this presents questions and answers in a List or Card view.
- [x] Selected choices are marked as user taps their choice (but answers are not presented yet!).
- [x] User can submit choices and is presented with a score on trivia game.

The following **optional** features are implemented:

- [x] User has answer marked as correct or incorrect after submitting choices (alongside their score).
- [x] Implement a timer that puts pressure on the user and auto submits choices after the timer expires.

The following **additional** features are implemented:

- [x] Loading indicators appear while fetching categories and questions.
- [x] Error messages explain connection problems, unavailable question combinations, and API rate limits.
- [x] Users can change their selected answer before submitting.
- [x] Unanswered questions are labeled in the results.
- [x] Play Again returns to the Options screen to create another game.
- [x] Answer review uses text and icons alongside colors to indicate correctness.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

https://www.loom.com/share/668f41bc4f314d30b61a7968ecd44036

## Notes

No particular obstacles encountered. 

The app uses SwiftUI for its interface, URLSession for networking, and Codable for JSON decoding. Questions appear in a List view. The optional timer provides a shared budget of 30 seconds per question.

The project passed an iOS simulator build. Complete interactive testing and record a walkthrough before submitting.

Trivia questions are provided by the [Open Trivia Database](https://opentdb.com/) under the [Creative Commons Attribution-ShareAlike 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/). The Apache license below applies to the app source code; trivia content retains its separate license.

## License

    Copyright 2026 Nafisa Nusha

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
