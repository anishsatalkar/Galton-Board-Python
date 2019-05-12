# Galton Board in Python
A simple Galton board simulation in pure Python.
Michael from Vsauce has an amazing video explaining the concept : https://www.youtube.com/watch?v=UCmPmkHqHXk

## Requirement
Tested on Python3.6. Doesn't require any additional libraries.

## How to use (non programmers)
### Windows
1. Download and install Python from https://www.python.org/downloads/
2. From this page itself, click on the "Clone or download" button and then click on "Download ZIP".
3. Extract the zip.
4. Open `Command Prompt` (CMD) and navigate to the folder where the ZIP file has been extracted using `cd` command. For more help : https://www.youtube.com/watch?v=sjaCgavMO18
5. Once you are in that folder, copy and paste `python galton.py 15 200` command into the Command Prompt. 
15 is the number of levels (height) of the board and 200 is the number of balls that would be used for the simulation. You may use any positive whole number for those 2 values.

## How to use (programmers)
### Windows
1. Just follow the step 5 from the previous explanation.

### Linux
1. In Terminal use the `python3 galton.py [height] [balls]` command were height and balls are integer values.



## Output example:
```
0

0

1
.
12
............
34
..................................
46
..............................................
71
.......................................................................
56
........................................................
50
..................................................
34
..................................
13
.............
2
..
2
..
0
```
