# book-club-tdd

The goal is to create a function that can calculate the score of a single roll of dice in the dice game "1000".

## The (simplified) scoring rules of 1000 the dice game

Players roll six dice which are scored in the following fashion:

- A roll of 1 scores 100 points and a roll of 5 scores 50 points
  - Ex: If you roll  2, 1, 4, 1, 6, 5, your score would be 250 because you rolled 2 ones and one 5
- Rolling three-of-a-kind scores you 100 times the number you rolled three times 
  - Ex: Rolling 3 twos scores 200 points
  - Ex: Rolling 3 fours scores 400 points
- Exception: Rolling three ones scores 1000 points
- Rolling four-of-a-kind scores double of the three-of-a-kind roll
  - Ex: Rolling 4 twos scores 400 points
  - Ex: Rolling 4 fours scores 800 points
- Rolling 1,2,3,4,5,6 scores 1500 points
