![CS121 Banner](images/CS121-BANNER.svg)
# Module 4 Lab Guide (part 2)
[Lab Introduction](https://boisestate.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=f5119edd-cac4-4b02-9901-ae240170c28e&start=0)  

**NOTE: Please remember to [open the workspace](images/open-lab-workspace.png) before beginning on the lab activities** 

## Lab Activity 2 - VowelCounter
### Problem Description
Design and implement an application that reads a string from the user and then determines and prints how many of each lowercase vowel (a,e,i,o, and u) appear in the entire string. Have a separate counter for each vowel. Also count and print the number of nonvowel characters. Your program should match the expected output below.

#### Expected Program Output (with sample user input)
```
Enter a string of characters:
Mississippi River

Number of each lowercase vowel in the string:
a: 0
e: 1
i: 5
o: 0
u: 0
other characters: 11
```

#### Expected Program Output (with sample user input)
```
Enter a string of characters:
Life is like a box of chocolates, you never know what you're gonna get...

Number of each lowercase vowel in the string:
a: 4
e: 7
i: 3
o: 8
u: 2
other characters: 49
```

### Implementation Guide
1. Expand the folder named VowelCounter and create a new file named VowelCounter.java
2. Design a program to satisfy the requirements in the Problem Description and enter the program code in VowelCounter.java
3. Test the program with the sample user input using the run link above the main method. Carefully think about each of the different cases you'll need to test for to verify that the application is functioning properly.
4. Commit the changes to your local repository with a message stating that Lab Activity 2 is completed.
5. Push the changes from your local repository to the github classroom repository.

## Lab Activity 3 - RockPaperScissors
### Problem Description
Design and implement an application that plays the Rock-Paper-Scissors game against the computer. When played between two people, each person picks one of three options (usually shown by a hand gesture) at the same time, and a winner is determined. In the game, Rock beats Scissors, Scissors beats Paper, and Paper beats Rock. 

The program should randomly choose one of the three options (without revealing it) and then prompt for the user's selection. At that point, the program reveals both choices and prints a statement indicating whether the user won, the computer won, or it was a tie. Continue playing until the user chooses to stop. Then print the number of user wins, losses, and ties. Your program should match the expected output below.

#### Error Handling
For this activity you may assume that the user can follow directions and will only enter appropriate values (1,2,3) or (y,n) as appropriate. Please focus your time on correct implementation of the game logic and lots of testing. :)

#### Expected Program Output (with sample user input)
```
Enter your choice - 1 for Rock, 2 for Paper, and 3 for Scissors: 2
Computer chooses Rock.
Human wins!

Play again (y/n)? y 

Enter your choice - 1 for Rock, 2 for Paper, and 3 for Scissors: 3
Computer chooses Rock.
Computer wins!

Play again (y/n)? y

Enter your choice - 1 for Rock, 2 for Paper, and 3 for Scissors: 2
Computer chooses Scissors.
Computer win!

Play again (y/n)? y

Enter your choice - 1 for Rock, 2 for Paper, and 3 for Scissors: 1
Computer chooses Paper.
Computer wins!

Play again (y/n)? y

Enter your choice - 1 for Rock, 2 for Paper, and 3 for Scissors: 1
Computer chooses Rock.
We tied!

Play again (y/n)? n

You won 1 time.
You lost 3 times.
We tied 1 time.
```

### Implementation Guide
1. Expand the folder named RockPaperScissors and create a new file named RockPaperScissors.java
2. Design a program to satisfy the requirements in the Problem Description and enter the program code in RockPaperScissors.java
3. Test the program using the run link above the main method. Carefully think about each of the different cases you'll need to test for to verify that the application is functioning properly.
4. Commit the changes to your local repository with a message stating that Lab Activity 3 is completed.
5. Push the changes from your local repository to the github classroom repository.
