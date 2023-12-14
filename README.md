# WhatsApp-A-Mole: Interactive Game for Generating Awareness on Privacy on WhatsApp

## Game Link: [Link](https://pankilkalra.github.io/cse648-psosm-project/)

## About
WhatsApp-A-Mole is an interactive, fun game that aims to generate privacy awareness through questions based on the privacy policy and settings of WhatsApp.

How does it work?
WhatsApp-A-Mole is inspired by the classic arcade game, Whack-A-Mole. The game interface is divided into 2 parts. The first presents multiple choice questions related to privacy on WhatsApp, where each option is colour-coded. The second simultaneously presents colourful moles, where each mole corresponds to an option for the current question. Your aim is to whack the mole corresponding to the correct answer. 
For every correct answer, you score points. For every incorrect answer, you lose a life. As the game progresses, there are 3 levels of questions (easy, medium, hard) with corresponding scores (+1, +2, +3). The game ends when you lose all 3 lives or the 3 minute timer runs out, and your score is added to the leaderboard. 
  
## Implementation
We programmed the game using Vanilla JavaScript and used HTML CSS for the style elements of the game. The game is divided into different menus: Main Menu, Game, Leaderboard, Instructions, and Privacy Policy. For the main game, we used transitions to move the timer and to sprout the moles. For the leaderboard, a firebase realtime database was used to store the usernames and corresponding scores of everyone who played the game in real time.

## Demo of the game (Youtube Video):
[![Demo](http://img.youtube.com/vi/CfUPYbwZaQY/0.jpg)](https://www.youtube.com/watch?v=CfUPYbwZaQY "Demo")

Please refer to the blog published [here](https://cse648psosm2021.blogspot.com/2021/05/whatsapp-mole-interactive-game-for.html) for additional details.

## Directory Structure
* [index.html](indel.html) - contains the base html layout and the js script for the game
* [style.css](style.css)  - contains the style elements
* [assets](assets/) - contains the image and audio files used in the game

### Project was done as part of PSOSM course in the Winter 2021 semester of IIITD under the guidance of Prof. Ponnurangam Kumaraguru. This was the tech team: 
* Aneesha Lakra
* Daksh Thapar
* Himanshu Raj
* Jasmine Kaur 
* Meeha Tiwari
* Naman Tyagi 
* Pankil Kalra
* Rachit Bhanaya
* Rishabh Devgon
