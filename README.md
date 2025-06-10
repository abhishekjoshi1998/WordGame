
## JavaScript Concepts Utilized

This project was a great opportunity to apply and solidify understanding of several key JavaScript concepts:

-   **Arrays & Objects:** The word list in `words.js` is an array of objects, with each object holding a `word` and a `hint`.
-   **Functions:** Logic is modularized into functions like `initGame()`, `checkWord()`, and the timer function to keep the code clean and reusable.
-   **DOM Manipulation:** Extensively used to dynamically update the HTML content, such as displaying the scrambled word, hint, timer, and feedback messages.
-   **String Manipulation:** Methods like `split()`, `sort()`, `join()`, and `toLowerCase()` are used for scrambling the word and comparing user input.
-   **Event Listeners:** The `addEventListener()` method is used to handle `click` events on the "Check Word" and "Refresh Word" buttons.
-   **Conditional Statements:** `if/else` blocks are crucial for checking if the guessed word is correct, managing the timer, and providing feedback to the player.
-   **Timers (`setInterval`):** The `setInterval` function is used to create the 30-second countdown timer, updating the display every second.

## Setup and Local Installation

To run this project on your local machine, follow these simple steps:

1.  **Clone the repository (if you have one on GitHub):**
    ```sh
    git clone https://github.com/abhishekjoshi1998/WordGame.git
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd WordGame
    ```

3.  **Open the `index.html` file:**
    You can simply open the `index.html` file directly in your web browser. For a better development experience, use a live server extension (like "Live Server" in VS Code).