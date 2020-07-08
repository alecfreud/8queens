# 8queens
8 Queens Problem with Random Restart Hill Climbing

simple c# implementation:

- generates random starting state of 1 queen per column

- checks number of queen interactions based on chess rules (horiz + diagonal) + assigns to H value

-  moves each queen through her column and checks for a lower H. Each queen reset to starting position before moving to next column

- starting state updates to current state if H value is lower. number of lower states is counted

- if no lower state is found during all neighbor checks, current state is randomly restarted

- each state and associated H value is printed out (simple graphical conversion from int array to 8x8 1s & 0s), along with the number of neighbor states with lower H.

- solution state is printed along with the total state changes & number of restarts
