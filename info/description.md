Think back to the game Tic-Tac-Toe, sometimes also known as Xs and Os. This is a game for two players (X and O)
who take turns marking the spaces in a 3×3 grid.
The player who succeeds in placing three respective marks 
in a horizontal, vertical, or diagonal rows (NW-SE and NE-SW) wins the game.

But we will not be playing this game.
You will be the referee for this games results. 
You are given a result of a game and you must determine 
if the game ends in a win or a draw as well as who will be the winner. 
Make sure to return "X" if the X-player wins and "O" if the O-player wins. 
If the game is a draw, return "D".

```
 X | . | O 
-*-|---|---
 X | X | .   X Wins
-*-|---|---
 X | O | O

 O | O | . 
---|-*-|---
 X | O | X   O Wins
---|-*-|---
 X | O | . 
 
 O | O | X 
---|---|---
 X | X | O   Draw
---|---|---
 O | X | X
```

A game's result is presented as a list of strings, 
where "X" and "O" are players' marks and "." is the empty cell.
