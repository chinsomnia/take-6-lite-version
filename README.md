# Take 6! Inspired Console Game

## Overview
This is a lite version of a CLI game inspired by the popular card game *Take 6!* (also known as *6 Nimmt!*). Unlike the original game, this version is designed as a 2-player game, consisting of a user player and a bot player. The gameplay has been simplified to offer a quick and enjoyable experience. This console game application was created as a weekend review project for the Voyager Bootcamp Program to help solidify the concepts learned about Unit Testing, Inheritance, Streams and Collections.

<img width="1593" alt="Screenshot 2024-09-02 at 1 31 40 PM" src="https://github.com/user-attachments/assets/0bcd3045-cb02-4554-8cdd-6b6c8cf2aad0">

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/chinsomnia/take-6-lite-version.git
2. Open the project with IntelliJ IDEA or any other preferred Java IDE.
3. Run the project using Main within the IDE.

## Usage
1. Click the Run button in your IDE.
2. Follow the on-screen instructions:
    - Enter your player name.
    - Choose and input the card numbers you wish to play in each round.
3. Enjoy the game as you compete against the bot!

## Features
- Two-Player Mode: Play against a bot.
<img width="566" alt="Screenshot 2024-09-02 at 1 34 23 PM" src="https://github.com/user-attachments/assets/266dcc7a-b8f8-4fea-8d12-13a035671d55">

- Simplified Gameplay: A quick and accessible version of the original Take 6! game.
<img width="559" alt="Screenshot 2024-09-02 at 1 34 44 PM" src="https://github.com/user-attachments/assets/7bc02348-3efd-4cfe-886d-249f2b1b6c89">

- Console-Based: Runs directly in the terminal/console.
<img width="564" alt="Screenshot 2024-09-02 at 1 37 39 PM" src="https://github.com/user-attachments/assets/c33d28ae-2388-475b-8b92-bb89df744846">

## How to Play  

### Objective  
Avoid collecting penalty points! The player with the fewest points at the end of the game wins.  

### Game Setup  
- The game consists of a deck of numbered cards, each with a penalty value.  
- Both the user and the bot receive a hand of cards.  
- Four starting cards are placed in separate rows on the board.  

### Gameplay  
1. **Choose a Card** – The user and the bot simultaneously select a card from their hand.  
2. **Card Placement** – The selected cards are placed in the appropriate row based on their number:  
   - A card must be placed in the row where it is the next highest number.  
   - If a row reaches its limit (e.g., 5 cards), the player who adds the 6th card must take the entire row.  
   - The penalty points collected are equal to the sum of the numbers on the taken cards.  
3. **Repeat** – Play continues until all cards have been placed.  

### Winning the Game  
- The game ends when all cards have been played.  
- The player with the fewest total penalty points (sum of all collected card numbers) wins.  

## Technologies Used
Java

## Contributing
Contributions are welcome! Please follow these guidelines:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push the branch.
4. Submit a pull request for review.
   
## License
This project is not licensed, and it is important to note that no copyright infringement is intended. The game is simply inspired by the original Take 6! (6 Nimmt!) card game, and this version is for educational and entertainment purposes only.

## Contact
- GitHub https://github.com/chinsomnia/
- LinkedIn https://www.linkedin.com/in/chinantalan/
