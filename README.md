# RiddleGame

RiddleGame is a simple command-line Java application that presents the user with riddles and keeps track of their score. The user can ask for hints if they are stuck, and the game will inform them of the correct answer if they are unable to guess it.

## Features

- Randomly selects a riddle from a predefined list.
- Allows users to guess the answer to the riddle.
- Provides hints if the user requests one.
- Tracks the user's score and the number of hints used.
- Allows the user to continue playing or exit the game.
- Displays the final score and the number of hints used at the end of the game.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your machine.

### Running the Game

1. Clone the repository or download the `RiddleGame.java` file to your local machine.
2. Open a terminal and navigate to the directory containing the `RiddleGame.java` file.
3. Compile the Java file using the following command:
    ```sh
    javac RiddleGame.java
    ```
4. Run the compiled Java program using the following command:
    ```sh
    java RiddleGame
    ```

## How to Play

1. The game will display a riddle.
2. Type your answer and press Enter.
3. If your answer is correct, you will be notified, and your score will increase.
4. If your answer is incorrect, you will be asked if you want a hint.
    - If you choose to receive a hint, a hint will be displayed, and you will get another chance to answer the riddle.
    - If you decline the hint, you can try to answer the riddle again.
5. If you are unable to guess the correct answer even after a hint, the game will display the correct answer.
6. You can choose to continue playing or exit the game.
7. At the end of the game, your final score and the number of hints used will be displayed.

## Example
Riddle: I speak without a mouth and hear without ears. I have no body, but I come alive with the wind. What am I? Your answer: A shadow Wrong! Would you like a hint? (yes/no) yes Hint: This thing is known for its ability to reflect sound. Try again: Your answer: An echo Correct! Continue playing? (yes/no) yes Riddle: The more you take, the more you leave behind. What am I? Your answer: Footsteps Correct! Continue playing? (yes/no) no Your final score: 2 Hints used: 1 Thanks for playing!
