# ReactJS MCQ Quiz Game App

This project is a ReactJS-based Multiple Choice Question (MCQ) game application designed to provide an engaging and interactive quiz experience. The app features seamless navigation with three primary pages: Start, Quiz, and Result. It uses context to manage and share data across the application, ensuring a smooth and consistent user experience.

## Features

- **Start Page**: The entry point where users can begin the quiz.
- **Quiz Page**: Displays questions one at a time, tracks user progress and score.
- **Result Page**: Shows the final score after completing the quiz.

## Components

- **Start Component**: Introduces the quiz and allows the user to start the game.
- **Quiz Component**: Displays each question and its options, handling user interactions and answer submissions.
- **Result Component**: Shows the final score and provides feedback.

## Data Management

The application uses a context (`DataProvider`) to manage state and share data across components. This context stores quiz data, user responses, and the current score.

## Project Structure

- **App.js**: The main entry point that sets up the routing and context provider.
- **components/Start.js**: The start page component.
- **components/Quiz.js**: The quiz page component.
- **components/Result.js**: The result page component.
- **context/dataContext.js**: Contains the context and provider for managing application state.

## Getting Started

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Dipesh12chourasiya/mcq-game.git
   cd mcq-game
2. Write :
   ```bash
   npm i 
   npm start


This `README.md` provides a comprehensive overview of the project, including its features, setup instructions, and deployment guidelines.
