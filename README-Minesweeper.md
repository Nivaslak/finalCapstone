# Mine Sweeper Game

This Python script implements a simple Mine Sweeper game. It takes a predefined minefield represented by a 2D array and prints out the number of adjacent mines for each spot.

## Usage

1. Clone the repository to your local machine.
2. Open the script in a Python environment.
3. The minefield is already defined within the script. You can modify the minefield by changing the values in the `minefield` array.
4. Run the script.
5. The program will print the minefield with the number of adjacent mines for each spot.



## Explanation
A function that takes a grid of # and -, where each hash (#) represents a
mine and each dash (-) represents a mine-free spot is created.
Return a grid, where each dash is replaced by a digit, indicating the number of
mines immediately adjacent to the spot i.e. (horizontally, vertically, and
diagonally).

![image](https://github.com/Nivaslak/finalCapstone/assets/134709899/c70f020c-e030-43f6-9f80-2572a9cc400e)




!![image](https://github.com/Nivaslak/finalCapstone/assets/134709899/8933ad67-76b5-409e-85d3-dcdac54e81ae)



Here is a tip. When checking adjacent positions to a specific position in the grid,
the following table might assist you in determining adjacent indexes:

![image](https://github.com/Nivaslak/finalCapstone/assets/134709899/1e28c81d-2810-430d-b0f0-f4a21f5650a8)

Also ensure that when checking adjacent positions in the grid that you take into
account that on the edges of the grid, you may go out of bounds.

