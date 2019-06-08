# game-of-life
Conway's game of life features a simple simulation that utilizes rules to create a phenomenon of cells living and dying. Per Wikipedia's entry that describes the rules:

    1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.
    2. Any live cell with two or three live neighbours lives on to the next generation.
    3. Any live cell with more than three live neighbours dies, as if by overpopulation.
    4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.
    
This particular software project is a C# application that utilizes two dimmensional arrays and nested for loops to simulate cells living and dying, programmatically creating the rules above using conditional statements. 

In this software project, however, the user must edit the source code that determines where cells go in which parts of the array. Future plans include creating a menu system that prompts a user to select specific shapes where cells are initially placed and/or a more interactive method of placing cells onscreen.
