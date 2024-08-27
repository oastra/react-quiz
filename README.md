# React Quiz

React Quiz is an interactive quiz application built with React. It allows users to test their knowledge on various topics with a set of questions, providing instant feedback and scoring. The application features a start screen, question display, progress tracking, and a final screen showing the user's score.

## Features

- Start screen to welcome users and provide an overview of the quiz.
- Question display with multiple choice answers.
- Immediate feedback on selected answers.
- Progress tracking through the quiz.
- Final score display with an emoji based on the user's performance.
- Ability to restart the quiz.

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js**: You can download it from [nodejs.org](https://nodejs.org/).
- **npm**: Node Package Manager is included with Node.js.

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/react-quiz.git
   ```

   `cd react-quiz`

   `npm install`

   ``npm start`

### Available Scripts

In the project directory, you can run:

`npm start`
Runs the app in development mode.
Open http://localhost:3000 to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

`npm test`
Launches the test runner in the interactive watch mode.
See the section about running tests for more information.

`npm run build`
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

`npm run eject`
If you aren’t satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.

`npm run server`
Runs a JSON server to serve the quiz questions. The server will run on http://localhost:8000. This script uses the json-server package to simulate a backend for fetching questions.

### Project Structure

-**index.js**: The entry point for the React application, where the root component is rendered.

-**App.js**: The main component that handles the quiz logic, including fetching questions, managing state, and displaying different screens.

-**components/**: Contains the components used in the quiz, such as Header, StartScreen, Question, NextButton, FinishScreen, and more.

-**index.css**: Contains all the styles used in the application to ensure the app is visually appealing and responsive.

-**package.json**: Manages the dependencies and scripts for the project.

### Author

Olha Chernysh
