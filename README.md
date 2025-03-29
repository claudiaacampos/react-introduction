# React Essentials App

This project is a React-based application designed to demonstrate and explain core React concepts such as Components, JSX, Props, and State. It provides interactive examples and descriptions to help users understand these fundamental concepts.

## Features

- **Core Concepts Section**: Displays a list of React's core concepts with images, titles, and descriptions.
- **Examples Section**: Allows users to explore interactive examples of React concepts, including code snippets and explanations.
- **Dynamic UI**: Utilizes React's state management to dynamically update the UI based on user interactions.

## Project Structure

The project is organized as follows:

```
src/
├── App.jsx                # Main application component
├── index.jsx              # Entry point for the React app
├── index.css              # Global styles
├── components/            # Reusable React components
│   ├── Header/            # Header component and styles
│   ├── CoreConcepts.jsx   # Displays the list of core concepts
│   ├── CoreConcept.jsx    # Represents a single core concept
│   ├── Examples.jsx       # Interactive examples section
│   ├── Section.jsx        # Generic section wrapper
│   ├── TabButton.jsx      # Button for tab navigation
├── assets/                # Static assets (images, icons)
└── data.js                # Data for core concepts and examples
```

## How It Works

### Core Concepts Section

The `CoreConcepts` component renders a list of React's core concepts using data from [`data.js`](data.js). Each concept is displayed as a card with an image, title, and description.

### Examples Section

The `Examples` component provides an interactive way to explore React concepts. Users can select a topic (e.g., Components, JSX, Props, State) using tab buttons, and the corresponding example is displayed dynamically.

Key components used:
- [`TabButton`](src/components/TabButton.jsx): Renders a button for selecting a topic.
- [`Section`](src/components/Section.jsx): Wraps the examples section.
- State management with `useState` to track the selected topic.

### Header

The `Header` component displays the app's title and a random description from a predefined list.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open the app in your browser at `http://localhost:5173`.

## Technologies Used

- **React**: Frontend library for building the UI.
- **Vite**: Development server and build tool.
- **CSS**: Styling for the application.

## Screenshots

### Core Concepts Section
![Core Concepts](src/assets/react-core-concepts.png)

### Examples Section
![Examples](src/assets/state-mgmt.png)

