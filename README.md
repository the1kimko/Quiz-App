# Quiz App README.md

## Introduction
This repository contains the code for a quiz application built using `HTML`, `CSS`, and `JavaScript`. The application fetches questions from the Open Trivia DB API, tracks high scores, and provides an interactive user experience. It incorporates modern JavaScript features and utilizes Local Storage for saving user data.

## Key Features
1. High Score Tracking: Saves high scores in Local Storage.
2. Progress Bar: Visually indicates the user's progress through the quiz.
3. Loader Animation: Displays a spinning loader icon while questions are being fetched.
4. Dynamic HTML Generation: Generates quiz questions and answers dynamically using JavaScript.
5. API Integration: Fetches trivia questions from the Open Trivia DB API.
6. Modern JavaScript Techniques: Utilizes ES6 features such as arrow functions, spread operator, and template literals.
7. Responsive Design: Styled with CSS Flexbox and animations for a better user experience.

## Technologies Used
- `HTML`: For structuring the web application.
- `CSS`: For styling the application (Flexbox, animations, REM units).
- `JavaScript`: For implementing logic (Array functions, Fetch API, Local Storage).

## Steps to Build the Application
- Create and Style the Home Page
Set up the home page layout and style it using CSS.
- Create and Style the Game Page
Develop the game interface that will display questions.
- Display Hard-Coded Questions
Initially load questions from a hard-coded array to test styling.
- Feedback for Answers
Provide instant feedback for correct or incorrect answers.
- Heads Up Display (HUD)
Create a HUD to show current score and question number.
- Progress Bar Implementation
Add a progress bar to visually track quiz progress.
- End Page Creation
Design an end page to display final scores and options to save or restart.
- High Scores in Local Storage
Implement functionality to save high scores using Local Storage with JSON methods.
- Load High Scores
Create a dedicated page to display high scores pulled from Local Storage.
- Fetch Questions from Local JSON File
Transition from hard-coded questions to loading them from an external JSON file.
- Fetch Questions from Open Trivia API
Use Fetch API to retrieve trivia questions dynamically.
- Create a Spinning Loader
Implement a CSS spinner that displays while fetching questions.

## How to Run the Application
1. Clone this repository:
```bash
git clone <YOUR_REPOSITORY_URL>
```
2. Navigate into the project directory:
```bash
cd <YOUR_PROJECT_DIRECTORY>
```
3. Open index.html in your web browser or use a live server extension in your code editor for a better experience.

## License
This project is licensed under the MIT License. See the LICENSE file for details.