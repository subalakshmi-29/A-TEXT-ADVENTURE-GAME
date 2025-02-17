# Text Adventure Game in Java

## Overview
This is a simple text-based adventure game written in Java. The game allows players to make choices that affect the outcome of their adventure. Players can explore different locations, encounter various challenges, and collect points based on their decisions.

## Features
- **Interactive Choices**: Players can choose different paths and actions.
- **Random Events**: Some outcomes are determined by random events, adding an element of surprise.
- **Score System**: Players earn points based on their successful actions.
- **Health System**: Players have a health score that can lead to game over if depleted.

## How to Play
1. **Start the Game**: Run the `Main` class to start the game.
2. **Make Choices**: Follow the prompts to make choices by entering the corresponding numbers.
3. **Explore**: Explore different locations like the Dark Cave and the Enchanted Forest.
4. **Face Challenges**: Encounter challenges and make decisions that affect your health and score.
5. **Game Over**: The game ends when you choose to end it or when your health reaches zero.

## Code Structure
- **Main Class**: Contains the main method and initializes the game.
- **confir()**: Handles the initial game menu and choices.
- **startGame()**: Starts the game and presents the initial choices.
- **exploreCave()**: Handles the cave exploration scenario.
- **enterForest()**: Handles the forest exploration scenario.
- **exploreRandom()**: Generates random outcomes for certain events.
- **pause()**: Pauses the game and waits for user input.
- **clear()**: Clears the console screen.

## Requirements
- **Java Development Kit (JDK)**: Ensure you have JDK installed on your system.
- **IDE or Text Editor**: Use an IDE like IntelliJ IDEA, Eclipse, or a text editor like VS Code.

## Running the Game
1. **Compile the Code**: Open a terminal and navigate to the directory containing the Java file. Run the following command to compile the code:
   ```sh
   javac Main.java
   ```
2. **Run the Game**: After compiling, run the game using:
   ```sh
   java Main
   ```

## Example Gameplay
```
Welcome To The Text Adventure Game!

1. Start The Game
2. End The Game
Enter Your Choice: 1

You Find Yourself In A Mysterious Place:
1. Explore The Dark Cave
2. Walk Through The Enchanted Forest
Enter Your Choice: 1

You Enter The Dark Cave And Discover A Treasure Chest!
1. Open The Chest
2. Leave The Cave
Enter Your Choice: 1

You Find Out Treasure!
Your Score: 20
You Are Now Good To Go Ahead

1. Start The Game
2. End The Game
Enter Your Choice: 2

Game Over!
Your Health Score: 100
You Collected Score: 20
```

## Contributing
Feel free to fork this project and contribute by adding new features, improving the code, or fixing bugs. Pull requests are welcome!

## License
This project is open-source and available under the MIT License.

## Acknowledgments
- Inspired by classic text-based adventure games.
- Special thanks to the Java community for providing excellent resources and documentation.

Enjoy the game and happy coding!
