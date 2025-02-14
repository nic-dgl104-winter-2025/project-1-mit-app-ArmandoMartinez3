[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/so8F8uYz)
# MIT App Inventor Project - K Learning

K learning is an application designed so that you can learn a little about the history of the indigenous community "K'ómox", a little about the history of how what we know today as Comox Valley was formed, through the application you will be able to see different screens, each one dedicated to different content along with images that you can later relate to take a quiz that the application contains.

This app is a simple educational quiz that uses images and associated questions to test the user's knowledge. As the user answers questions, the score is updated in real time. The app displays an image for each question and prompts for a response. At the end of the quiz, the final score is presented.

## Features
* Screen to Read The History of Comox Valley
* Screen to Read about K'ómox Community
* Screen to See some Art
* Screen to Do a Quiz about all the Content

| ![HomeScreen](https://github.com/user-attachments/assets/0aa1e8e0-bc5d-4211-80ff-e7b6a7da58ad) | ![HistoryScreen](https://github.com/user-attachments/assets/81daaa73-c385-4305-9929-61bbb76645d6) | ![CommScreen](https://github.com/user-attachments/assets/e82a7ec6-d460-4aff-8e04-9d49660cae5a) | ![ArtScreen](https://github.com/user-attachments/assets/159e9fe0-d29c-4e88-a771-2d853707c64d) | ![QuizScreen](https://github.com/user-attachments/assets/80a05bc1-5ca1-43fc-b890-54c38a9b8725) |
|----------------------------------------------|----------------------------------------------|----------------------------------------------|----------------------------------------------|----------------------------------------------|

## Guide to Open .aia

1. Download the .aia fron this repository
2. Open MIT App Inventor
3. Click on Projects
4. Click on Import project (.aia) from my computer
5. Click on Project KLearning.aia


## Development of K Learning

**1. Game Initialization:**
  * The global variables `score`, `questionNumber`, `imageList`, and `answerList` are initialized.
  * When the `QuizScreen` is started, the `showQuestion` function is called and the initial visibility buttons are set.

![image](https://github.com/user-attachments/assets/cc4b3bab-72c0-4a8c-ba4c-4885a73eb00f)

**2. Question Display:**
  * The `showQuestion` function updates the displayed image based on the `questionNumber`.
  * When the end of the questionnaire is reached, it displays the final result and the `homeButton` to return to the home screen.

![image](https://github.com/user-attachments/assets/85499b11-74d6-4de8-9c06-b6ac7b9b9dcf)

**3. Answer Checking:**
  * Clicking `submitButton` compares the text entered by the user (answer.Text) with the corresponding answer from the `answerList`.
  * If correct, `correctSound` is played, the score is increased, and a success message is displayed.
  * If incorrect, `wrongSound` is played and the correct answer is indicated.

![image](https://github.com/user-attachments/assets/245f8d9b-dec1-4c39-93f8-5c6b308ed1f9)

**4. Navigation:**
  * The `nextButton` button allows you to move on to the next question.
  * The `homeButton` button redirects the user to the main screen.

![image](https://github.com/user-attachments/assets/e58c092f-67a6-4679-8af0-7a46832cfc7d)

## Code Review

**Strengths:**
  * Clear structure: A logical flow is used to manage questions.
  * Modularity: Appropriate use of lists to store images and answers.
  * Interactivity: Immediate response from the system when entering answers.

**Areas for Improvement:**
  * Answer Validation: Not case sensitive with `upcase`, but could be improved with more specific messages.
  * Maintenance: List length is fixed in some comparisons. Using `length` of list always ensures flexibility if more questions are added.
  * UI Optimization: Transition between questions could be optimized with `smoother visual feedback`.

**Areas for Improvement:**
  * Answer Validation: Not case sensitive with `upcase`, but could be improved with more specific messages.
  * Maintenance: List length is fixed in some comparisons. Using `length` of list always ensures flexibility if more questions are added.
  * UI Optimization: Transition between questions could be optimized with `smoother visual feedback`.

## Resources used

https://ihosgallery.com/collections/masks-carvings

https://spiritsofthewestcoast.com/collections/the-thunderbird-symbol

https://www.youtube.com/watch?v=A6n31W_ils0

https://www.youtube.com/watch?v=VrPYnwPnHCI
