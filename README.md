# React Flashcards App

A responsive React-based flashcard application designed to make learning interactive and engaging. Users can click on a question card to reveal its answer, enabling a dynamic study experience. The app demonstrates React best practices, including state management, conditional rendering, and responsive design.

check it live at : https://flash-cards-roan.vercel.app/

## Features and Best Practices
- **Interactive Flashcards:** Each card displays a question, and clicking it reveals the answer. Clicking again hides the answer.
  
- **Responsive Design:**
  The app adapts seamlessly to various screen sizes. Cards stack vertically on smaller screens for optimal usability.

- **Dynamic State Management:**
  Utilizes the `useState` hook to manage the selection state of flashcards, ensuring smooth interaction.

- **Reusable Components:**
  Built with reusable functional components for scalability and maintainability.

- **Efficient List Rendering:**
  Renders flashcards dynamically using the `.map()` method.

## How It Works
- **Flashcard Interaction:** 
  1) By default, each card displays a question.
  2) Clicking on a card reveals the answer.
  3) Clicking the same card again hides the answer.

- **Responsive Design:**
  - On larger screens, flashcards are displayed in a grid layout with multiple columns.
  - On smaller screens, cards stack vertically for better usability.


## Technologies
- React (For building the interactive user interface.)
- JavaScript (For state management and rendering logic.)
- CSS (For styling and ensuring responsive design.)
