# Quiz App

Welcome to the Quiz App GitHub repository! This application is a simple quiz platform that allows users to answer a set of questions and receive feedback on their performance. Below, you'll find important information about the application, including its overview, setup instructions, assumptions made during development, and challenges faced.

## Overview

The Quiz App is a web-based application developed to provide users with an interactive quiz experience. Here are some key components and features of the application:

- **Quiz Questions**: The questions are fetched from the Open Trivia Database using the provided API URL.

- **Navigation**: Users can navigate through the quiz using the "Previous" and "Next" buttons. They can also submit their answers using the "Submit" button.

- **Timer**: A timer is included to limit the time available for completing the quiz. The timer is set to 30 minutes, and the quiz is automatically submitted when the time runs out.

- **Result Display**: After submitting the quiz, users can view their total marks obtained, the number of correct and wrong answers, and detailed question-wise feedback.

- **Responsive Design**: The application is designed to be responsive, adapting to different screen sizes.

## Setup Instructions

To set up the Quiz App locally, follow these instructions:

1. Clone the repository: `git clone https://github.com/your-username/quiz-app.git`
2. Navigate to the project directory: `cd quiz-app`
3. Open the `index.html` file in a web browser.

## Assumptions Made

During the development of the Quiz App, the following assumptions were made:

- The Open Trivia Database API (`https://opentdb.com/api.php?amount=15`) is assumed to be accessible and provide reliable quiz questions.

- The application assumes a fixed number of 15 questions in each quiz.

- The quiz is designed to be completed within a 30-minute time limit.

## Challenges Faced and Solutions

While developing the Quiz App, a few challenges were encountered:

1. **Fetching Questions**: Handling asynchronous fetching of questions from the API required the use of `async/await` in JavaScript to ensure smooth execution.

2. **Timer Implementation**: Managing the timer and updating it dynamically posed a challenge. The solution involved using JavaScript intervals to decrement the timer and updating the UI accordingly.

3. **Responsive Design**: Ensuring a consistent user experience across different devices and screen sizes required the use of CSS media queries.

## Feedback and Contributions

Feel free to provide feedback or contribute to the Quiz App by submitting issues or pull requests. Your input is valuable and can help improve the application.

Thank you for using the Quiz App! Happy quizzing!
