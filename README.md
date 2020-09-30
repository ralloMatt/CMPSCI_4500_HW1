# CMPSCI_4500_HW1
Javascript Project

The JavaScript code first starts out by making a two dimensional array to keep track of the number of touches for each cell. 
Each array index corresponds to an “x” and “y” coordinate for the center of each cell. 
Then a while loop begins and for every loop a direction is randomly selected. 
Then as each direction is being made I add or subtract to the x and y coordinates and add a touch to the cell corresponding to that coordinate. 
If I go off the grid, I go back to the previous cell and add a touch. 
When I’m at the far upper right of the grid x and y should both equal nine and the loop stops. Then I just display the results
