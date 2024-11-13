# Rendering Arrays in React

This project is a React lab focused on rendering components from an array of data stored in state.

## Project Overview

The objective of this project is to display a list of learner profiles, each with multiple scores, using React components and state management. The data includes each learner's name, bio, and score history, and the project demonstrates how to manage and render arrays in a React application.

## Requirements

- **Components**:
  - `App` component holds the `learners` array in its state and renders a `Learner` component for each learner.
  - `Learner` component renders the learner’s `name` and `bio`, and passes each score to the `Score` component.
  - `Score` component displays each score’s `date` and `score` properties.
- **Styling**: Layout and styling are left to the developer's discretion, but the project should have a clean, user-friendly interface.
  
## Project Setup

### Installation

Clone the repository and install dependencies:

```bash
git clone <repository_url>
cd <project_folder>
npm install
```

### Running the Project

To start the project in development mode:

```bash
npm start
```

This will open the project at [http://localhost:3000](http://localhost:3000).

### Production Build

To create an optimized production build:

```bash
npm run build
```

The build will be output in the `dist/` folder.

### Available Scripts

- `npm start`: Starts the development server with hot reloading.
- `npm run build`: Builds the project for production (optimized and minified).

## Technologies Used

- React
- Webpack
- Babel
- HTML, CSS

## Folder Structure

```
/dist               - Output folder for bundled code
/src                - Source files (React components, JS, etc.)
  /components       - React components
  /assets           - Static files (images, fonts, etc.)
/webpack.config.js  - Webpack configuration
/package.json       - Project metadata and dependencies
```

## Provided Data

The learners' data is initialized in the `App` component's state, structured as an array of learner objects. Each learner has a `name`, `bio`, and an array of `scores`.

---

Этот README.md достаточно краток и содержит все ключевые инструкции для работы с проектом.