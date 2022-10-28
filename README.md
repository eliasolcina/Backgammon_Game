# The Beautiful Game of Backgammon
### by Elias Olcina and Max Dinkelspiel

** This game is built in on a mac OS, therefore you may experience some bugs (mainly in terms of displaying the board and your moves). 

This game was created as our first project at NOD Coding Bootcamp (BC#4) 2022. The goal of the project was to improve our understanding of functional programming, therefore this game is very "function-heavy". We chose to create a backgammon game because we wanted a challenge, and backgammon is full of "case-dependent" rules and require a lot of conditional logic.

According to Wikipedia:
> *Backgammon is a two-player game of contrary movement in which each player has fifteen pieces, known traditionally as 'men' (short for 'tablemen') but increasingly known as 'checkers' in the US in recent decades. These pieces move along twenty-four 'points' according to the roll of two dice.* </br>
>
>![This is what the normal board looks like](https://i.imgur.com/koK7yPS.png)




This is how we present the board in the console for players to play. The board with the white background is the jupyter representation</br>
![The Game Board](https://i.imgur.com/eHEGr4J.png) 

The game is played by first rolling a die each to determine who goes first. The player with the highest roll use the dice just rolled to play their first turn. To make a move in the game, we prompt the user to input from which point they want to move a checker, and to which point they want to move it. Two random dice are generated for each turn.



```
Player 1 (●), your turn.
Remaining die/dice:
+ - - - - +   + - - - - +
|  o      |   |  o      |
|         |   |    o    |
|      o  |   |      o  |
+ - - - - +   + - - - - +

Current board:

P2 Finished Checkers:
  ₁ ₁ ₁ ₁ ₁ ₁   ₁ ₂ ₂ ₂ ₂ ₂
  ³ ⁴ ⁵ ⁶ ⁷ ⁸   ⁹ ⁰ ¹ ² ³ ⁴
|━━━━━━━━━━━━━━━━━━━━━━━━━━━|
| ●       o   | o         ● |
| ●       o   | o         ● |
| ●       o   | o           |
| ●           | o           |
| ●           | o           |
|             |             |
|━━━━━━━━━━━━━━━━━━━━━━━━━━━|
|             |             |
| o           | ●           |
| o           | ●           |
| o       ●   | ●           |
| o       ●   | ●         o |
| o       ●   | ●         o |
|━━━━━━━━━━━━━━━━━━━━━━━━━━━|
  ₁ ₁ ₁ ₀ ₀ ₀   ₀ ₀ ₀ ₀ ₀ ₀
  ² ¹ ⁰ ⁹ ⁸ ⁷   ⁶ ⁵ ⁴ ³ ² ¹
P1 Finished Checkers:
  
From which row do you want to move a marker? (1-24):
```
The numbers above and below the board are the indices that correspond to each point 

We have removed the PIP score and the doubling cube from the game since most people play without it, however, a future improvement to the project would be to add that functionality as well as the possibility to play against an AI.

In order to play the game you just have to download the python file and python it in your terminal/cmd. Once you get python going, you can play backgammon until the end of your days!

```
python main.py
```
