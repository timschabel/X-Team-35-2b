# X-Team 35 Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description
We want to implement a program that simulates rounds of blackjack.

The program's main class is outlined as follows:

- The user starts with $100 virtual dollars to bet with
- The game loop begins

- The deck of cards is shuffled (initialized, randomly put onto a stack)
- The user chooses how much they want to bet for the round
- The user would be shown their initial cards, and they would be given the option to hit or stay
- based on their input, a hit or stay method would be called
- if they stay, the program moves on
- if they hit, it keeps looping until the user busts or chooses to stay
- Once the user is done with their turn, the program simulates the dealer's hand
- If the dealer busts, or if they have a lower value than the user, the user wins.
- The user wins or loses the amount of money based on if they won

- This loop repeats until the user chooses to quit or if they run out of memory

The program would utilize a stack to simulate the deck of cards.
- Each individual card would be put onto the stack in a random order each time
- Since cards are never put back into the deck without shuffling, we don't have to worry about certain cards having precedence over others
- The cards would be popped off the stack when a new card is need in the program.

Testing
- With the deck
- test if the size of the deck is changing
- test if the suits are in the correct quantity
- test to see if there deck is in different orders each new round
- test to make sure all cards are able to be popped from the stack

- For the player
- Test to make sure the sum of the players hands are correct
- Test to make sure the player busts if their cards sum to over 21
- Test to make sure the player can't get any more cards after they bust
- Test to make sure the user enters a positive integer for their bet that can be covered by the amount of money they have, before they make any moves
- Test to make sure card is popped off the stack when the player hits
- Test to make sure card is not popped when the player stays

- For the dealer
- Make sure the user can only see the dealer's first card when the user is going
- Test to make sure the dealer busts if their cards sum to over 21
- Test to make sure the dealer can't get any more cards after they bust
- Test to make sure card is popped off the stack when the dealer hits
- Test to make sure card is not popped when the dealer stays
- Test to make sure the dealer wins if the user busts

- More
- Test to make sure the player is awarded the correct amount of money for the round if they win
- Test to make sure the player loses the correct amount of money if they lose
- Test to make sure the program ends if the user runs out of money


## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

BlackJack

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

The amount money for each players and win or lose for this round of game.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

the money that player bets on, the action of player take such as hit, stay, quit or continue.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.



Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

