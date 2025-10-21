# Hog
Hog is a dice game simulator that models two players competing to reach a target score using various strategic approaches. However, there are also three specific rules that players must abide by: Sow Sad, Boar Brawl, Sus Fuss. This project used mainly higher-order functions, control logic, and iteration. 

This project is a part of UC Berkeley's CS61A: Structure and Interpretation of Computer Programs course.

***All implementations from Problems 1-11 are entirely my own work.***

Sow Sad:
- If any of the dice outcomes is a 1, the current player's score for the turn is 1, regardless of the other values rolled.

Boar Brawl:
- A player who chooses to roll zero dice scores three times the absolute difference between the tens digit of the opponent’s score and the ones digit of the current player’s score, or 1, whichever is greater. The ones digit refers to the rightmost digit and the tens digit refers to the second-rightmost digit. If a player's score is a single digit, the tens digit of that player's score is 0.

Sus Fuss:
- We call a number sus if it has exactly 3 or 4 factors, including 1 and the number itself. If, after rolling, the current player's score is a sus number, their score instantly increases to the closest prime number greater than their current score. 





           
