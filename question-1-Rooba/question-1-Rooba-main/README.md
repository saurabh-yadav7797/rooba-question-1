# Question 1 Solution - Rooba

## Folder Structure (Updated)

The project is organized into the following components:

- `src/`: Contains the source code for the React application.
  - `components/`: Includes React components used in the application.
    - `LhsNavbar.jsx`: Left-hand side (LHS) navigation bar component.
    - `RhsMainContainer.jsx`: Main container component for the right-hand side (RHS) of the application.
      - `MainBoard.jsx`: Component responsible for the main content.
      - `RightSlot.jsx`: Component for the right slot.
      - `TernaryNav.jsx`: Ternary navigation component.
      - `TopBar.jsx`: Top bar component.
  - `App.js`: Main React component for the application.
  - `index.js`: Entry point for the React application.
- `src/styles/`: Contains stylesheets for the application.
  - `rightSlot.css`: Styles for the `RightSlot` component.

## Components (Updated)

### Right Slot (`RightSlot`)

The `RightSlot` component is a part of the `RhsMainContainer` and contains several sub-components:

- `MainBoard.jsx`: Main content display.
- `TernaryNav.jsx`: Ternary navigation controls.
- `TopBar.jsx`: Top bar for additional information.

## Assumptions

- It is assumed that when a user clicks on a button in the `Steps` component, the buttons corresponding to the steps below will be automatically enabled, allowing the user to proceed.


## Usage

To run the application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/thatcher-choice/question-1-Rooba.git
cd question-1-Rooba
npm install
npm start
