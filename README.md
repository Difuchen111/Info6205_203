# Info6205_203
Genetic Algorithm project - Pacman
Pac-man exists in a rectangular space of 10×10 grids. There are 40 beans and 10 bombs which are randomly placed in the 100 grids.
When Pac-man is born, it randomly appears in an arbitrary square. And what it needs to do is to use its own strategy to eat beans.
There are only 200 steps in total. If the Pac-Man eats a bean, it will get 10 points. If the Pac-Man eats a bomb, it will lose 3 points. 
If the Pac-Man knocks its head against a brick wall, it will lose 5 points. 
And it will also lose 1 point if it stops at a position in which there is no beans or bombs.
In theory, the highest score is to eat all the beans without deduction. 
There are 40 beans in total, which means in the ideal situation it can get 400 points.
According to the current state, Pac-Man decides to take the corresponding action. 
We use number 0 to 7 to respectively present the 8 actions, which are moving up, moving down, moving left, moving right, eating bombs, eating beans, staying and moving randomly. 
The purpose of this problem is to find out a strategy to get the highest-score in this Pac-Man game. 
