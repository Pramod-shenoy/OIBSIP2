# Number Guessing using JAVA
This repository contains a Number Guessing Game developed using Java and XML. The game challenges players to guess a randomly generated number within a set range, providing feedback on whether the guess is too high, too low, or correct. The game is easily configurable via an XML file, allowing customization of key parameters like the guessing range and the number of allowed attempts.

 # Features:
Random Number Generation: The game picks a random number within the range specified in the configuration file.
Feedback System: After each guess, the player is informed whether their guess was too high, too low, or correct.
XML-Based Configuration: Game settings, such as the number range (e.g., 1-100) and the maximum number of attempts, are managed via an XML configuration file. This allows easy modifications without altering the source code.
Flexible Attempts: The game can be configured to limit the number of guesses the player is allowed, adding an extra layer of challenge.
Console Interface: The game uses a simple, intuitive console-based interface where players can input their guesses and receive feedback.
Replay Option: After each game, players can choose to play again or exit.

 # How to Run:
Clone the repository to your local machine.
Open the project in your preferred Java IDE or run it via the command line.
Ensure the XML configuration file is set up with your desired game parameters.
Run the Java application, and the game will start in the console.
How to Configure the Game:
The XML file (config.xml) allows you to set the range for the random number and the maximum number of attempts.
Example of configuration options:
xml
Copy code
<game-config>
    <min-range>1</min-range>
    <max-range>100</max-range>
    <max-attempts>10</max-attempts>
</game-config>

# Technologies Used:
Java: The core game logic is written in Java.
XML: Configuration is handled through XML for flexible gameplay settings.
Possible Enhancements:
GUI Integration: Future versions could include a graphical user interface (GUI) using JavaFX or Swing.
Multiplayer Mode: An option to allow multiple players to guess the number in turns.
Score Tracking: Implementing a scoring system to track player performance over multiple rounds.
