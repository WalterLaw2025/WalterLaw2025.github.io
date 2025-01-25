# WalterLaw2025.github.io
Name: Walter Law
Email: wllaw@my.waketech.edu
This is my school account.
Description: This repository will hold assignments.
# About Me
## Interests I Have
* Anime
     * Anime I Currently Watch
  1. One Piece
  2. Solo Leveling
  3. Fire Force *(Rewatching to prepare for the new season.)*
* Video Games
     * Systems I Play On
  1. PS5
  2. XBox One
  3. Nintendo Switch
* Food and Restuarants
     * Korean BBQ
     * Sushi
     * Latin

## Recommended Websites
* [Crunchyroll Anime Website](https://www.crunchyroll.com/) - This is where I watch most of the anime I like.

* [Gamestop Website](https://www.gamestop.com/) - Some of my games are bought from here, though most are bought from in the store.
* Eat Happy, Be Happy
     * [KPot Korean BBq](https://thekpot.com/) - This is definitely one of my favorite places to eat. It is really good for groups but I also like to come by myself and even watch a little anime or other shows while savoring the delicious food.
     * [Okome House - Sushi](https://www.okomehouse.com/) - A restuarant that has quickly become a frequent lunch spot. The food is always fresh and for a good price. *I am currently trying to make my way through each item on the menu.*
     * [Yelp for Kumbala Sports Bar](https://www.yelp.com/biz/kumbala-bar-and-grill-raleigh) - A place that most would pass up but definitely has good food. The beans are the best I have had tasted in the area and they have other good selections too.


## Guessing Game


```mermaid
---
config:
  look: handDrawn
  theme: neutral
---
flowchart TD
    %% This is the start of the game.
    A[Press Start] -->|Computer generates random number 1 to 10| B(Please guess a number 1 to 10!)
    %% The computer will generate a number to be guessed and prompt for a number to be guessed.
    B --> C{Guessed number is input}
    %% The player will guess a number and input it to see if it is correct.
    C -->|Number is correct| D[Correct! Play again?]
    %% The input number is correct and the player can choose to play again.
    C -->|Number is incorrect| E{Computer checks if number is higher or lower than generated number}
    %% The computer notifies that the guessed number is incorrect and prompts player to try again with another guess. 
    E -->|Number is too high| F[Number is too high. Guess again, please!]
    %% The number guessed was too high and the player needs to guess a lower number.
    E -->|Number is too low| G[Number is too low. Guess again, please!]
    %% The number guessed was too low and the player needs to guess a higher number.
    E -->|Guess is a letter, character, or number not in range.| H[Incorrect input! Please try again!]
    %% Input is not within parameters of game. Player needs to try again within parameters.
    F --> B 
    %% Player is sent back to guess screen to input new number.
    G --> B 
    %% Player is sent back to guess screen to input new number.
    H --> B 
    %% Player is sent back to guess screen to input new number.
    D --> A
    %% The player will need to guess a new number.
```    
## This is a diagram of the flow of a guessing game. It shows how a player plays a guessing game and what happens when the computer responds to different inputs from the player.
