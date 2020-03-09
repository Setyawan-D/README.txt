Name: Darian W. Setyawan
ONID: 933-965-815
Section: CS 161-020
Assignment 5 Due Date: 3/8/2020

Description:

Welcome to the Treasure Chest of Books! You can add your own book to the chest at anytime, remove it, inspect it, generate a random book, or switch books position with one another. Your goal is to fill the chest with books as your own collection. Good Luck!

Instructions:

1) Compile the program with:

g++ -o assign5_treasure assign5_treasure.cpp

2) Run the program with:

./assign5_treasure

3) You will be asked to Enter how many rows and columns as the dimension of the chest. After you have filled the dimension, the program will present you with a menu and you will choose one of them.

The menu choices that will be presented are:
1: Add a book
2: Remove a book
3: Inspect a book
4: Generate a random book
5: Switch book positions
6: Exit.

If you select "Add a book", the program will display:

Enter the x coordinate:
Enter the y coordinate:

Note that your coordinates can't be below 0 or above the given dimension. For this example we will go with x = 0, y = 0
Enter the x coordinate: 0
Enter the y coordinate: 0

After you have filled the coordinate the program will ask you:

Enter a random number between 1-5:

If you guess the secret random number correctly, the value of your next book will be doubled!
If not, then nothing happens and it will continue.

The program will then ask you to enter the descriptions of the book.

Enter the title of the book: User input
Enter the author of the book: User
Enter the value of the book: $10000
Enter the year it was made: 2019
Enter the amount of pages it has: 4029

In this example of a 3x3 board,
The program will print out: 
 | U | _ | _ |  => ([0][0] [0][1] [0][2]) (This won't be printed out)
 | _ | _ | _ |  => ([1][0] [1][1] [1][2])
 | _ | _ | _ |  => ([2][0] [2][1] [2][2])
The total value right now is: $10000

If you chose the "Remove book" option, when you enter x = 0, y = 0
It will remove the board at [0][0] which will resulted on:

 | _ | _ | _ |  
 | _ | _ | _ |  
 | _ | _ | _ |  
The total value right now is: $0

If you chose the third option, when you enter x = 0, y = 0
It will print out:

The title of the book is: User input
The author of the book is: User
The value of the book is : $10000
The year the book was made: 2019
The amount of pages it has: 4029

 | U | _ | _ |  
 | _ | _ | _ |  
 | _ | _ | _ |  

If you chose the fourth option, when you enter x = 0, y = 0
It will print an error saying that the position has already been filled and will reprompt you.
When you enter x = 0, y = 1, it will print out:
 
 | U | R | _ |  
 | _ | _ | _ |  
 | _ | _ | _ |  

If you chose the fifth option, when you enter x = 0, y = 0
It will prompt for another x and y coordinate to where you want it to be moved. E.g x = 2 y = 0

 | _ | R | _ |  
 | _ | _ | _ |  
 | U | _ | _ |  
 
If the board is filled out, The program will give you a different menu

 | U | U | U |  
 | U | U | U |  
 | U | U | U |  
The total value right now is: $90000
 
The program will display a menu of:
 
2: Remove a book
3: Inspect a book
5: Switch book positions
6: Exit.

4) Limitations:
- If you enter a string of characters into the value of the book, year, and pages, the program will encounter an error and you will have to manually stop it with Ctrl+C.
- The program does not let you inspect a book that is empty and you can't return to the main menu. Manually stop the program with Ctrl+C.

5) Extra credit:
- The program will give different menus depending on the board.
- Added a luck aspect to the game in the add book part.
- Asked another person.
- Described one improvement in my word file.
