# Technologies Used
## 1. HTML
#### Purpose: Defines the structure and layout of the calculator interface.

#### Elements Used:
#### ~ `<div>`: Used for grouping calculator components, such as the display area and buttons.
#### ~ `<button>`: Represents the calculator buttons for numbers (`0-9`), operations (`+`, `-`, `×`, `÷`), and utility functions (e.g., Clear, `+/-`).
#### ~ `<input>`: Used to create the calculator's display screen, where the results and inputs are shown.
#### Role: Provides the skeleton of the calculator, allowing it to be interactive and user-friendly.

## 2. CSS
#### Purpose: Enhances the appearance of the calculator with styling and layout adjustments.
#### Properties Used:
#### ~ `background-color`: Defines the background colors for the calculator and buttons to make it visually appealing.
#### ~ `width` and `height`: Sets the dimensions for the calculator components, ensuring proper spacing and alignment.
#### ~ `border-radius`: Adds rounded edges to buttons for a modern, aesthetic look.
#### ~ `font-family` and `font-size`: Used to style the text for better readability.
#### Role: Ensures the calculator is visually organized and responsive to user interactions.

## 3. JavaScript
#### Purpose: Implements the logic for performing calculations and handling user interactions.
#### Key Functions:
#### ~ Event Handling: Captures button clicks using `addEventListener()` to process user inputs.
#### ~ DOM Manipulation: Updates the display screen dynamically using methods like `getElementById()` and `querySelector()`.
#### ~ Arithmetic Operations: Processes mathematical operations such as addition, subtraction, multiplication, and division.
#### ~ Special Functions: Implements additional functionality for:
#### i. Clearing the display (`Clear` button).
#### ii. Toggling between positive and negative values (`+/-` button).
#### Role: Enables real-time interactions, making the calculator fully functional and interactive.
