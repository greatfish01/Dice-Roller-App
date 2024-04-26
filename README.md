Dice Roller App

This Android/iOS app allows users to simulate rolling a six-sided dice. The app features a layout designed with relative positioning using ConstrainLayout (Android).
The code is using Kotlin. 

Features
Layout Design:
Utilizes ConstrainLayout (Android) or AutoLayout (iOS) for responsive and relative positioning of UI components.

Dice Quantity:
Displays the current number of dice to be rolled.
Includes buttons to increase (+) or decrease (-) the number of dice per roll (limited from 1 to 10 dice).

Dice Rolling:
Pressing the "Roll!" button rolls the dice. Each dice randomly generates a number, and the result is displayed.
The sum of the rolled numbers is shown.

Results List:
Uses a RecyclerView (Android) to list each roll's results.
Displays each roll's details, including individual dice outcomes.

Dice Display:
Utilizes image components to visually represent the outcome of each dice roll.

Interaction:
Newly rolled results are added to the top of the list, and the list automatically scrolls to display the latest result.
Long-pressing the "Roll!" button clears the results list. A toast message confirms the clear action.
