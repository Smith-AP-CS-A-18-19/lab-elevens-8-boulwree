# Elevens 8
Reece Boulware
Follow the instructions provided for Activity 8 in the student lab guide. This is more of an exploratory lab, so you will not need to copy any of your previous code into the repo. Answer the questions from the Student Guide in this document and ensure that you save and push the repo. You have one week to complete this lab.

1. Discuss the similarities and differences between *Elevens*, *Thirteens*, and *Tens*.

    * Board size, Ranks, suits, and Point value are similar; the differences are the moves that are legal and checking to see if another play is possible,

2. As discussed previously, all of the instance variables are declared in the `Board` class. But it is the `ElevensBoard` class that “knows” the board size, and the ranks, suits, and point values of the cards in the deck. How do the `Board` instance variables get initialized with the `ElevensBoard` values? What is the exact mechanism?

    * they use the "super" for the instance variables method and ElevensBoard uses inheritance the methods from the Board class

3. Now examine the files `Board.java` and `ElevensBoard.java`, found in this repository. Identify the `abstract` methods in `Board.java`. See how these methods are implemented in `ElevensBoard`. Do they cover all the differences between *Elevens*, *Thirteens*, and *Tens* as discussed in question 1? Why or why not?

    * the abstract methods are isLegal and anotherPlayIsPossible, and no because what is legal for Tens and Thirteens is different from what is legal for Elevens and same for what moves are possible 
