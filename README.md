# Ordering System

## How to run the program
Enter the following command to run the program:
```bash
$ python menu.py
```

## Program
The program provides the user with menu choices. The program provides the user with a total cost and receipt, based on the user's choices. Below find a step-wise guide to the running of the program:

### Category Choice
A menu is displayed for the user to choose from:
1. Snacks
2. Meals
3. Drinks
4. Dessert

Based on the user input the following outputs are displayed:
* A message stating that 'You have selected \<chosen category>' is displayed. Based on the input a sub-menu is displayed with prices.
* An error '\<Entered number> was not a menu option' is displayed, in case if user inputs a number other than the choices available.
* An error 'You didn't select a number' is displayed, in case if the user enters an input other than a number.

### Sub-menu choice
A sub-menu with items and prices is displayed in case if a valid category is entered by the user. The user is then asked to enter the item number they would like to order.

Based on the user input the following outputs are displayed:
* A message requesting the user to enter the the quantity for the chosen item. The user is also advised that the quantity will default to 1 in case if an invalid input is entered.
* An error message '\<Entered number> was not a menu option' is displayed, in case if user inputs a number other than the choices available.
* An error 'You didn't select a number' is displayed, in case if the user enters an input other than a number.

### Quantity
The user is prompted to enter the quantity for the chosen item, in case if the user enters a valid sub-menu choice. The quantity is set to 1 in case if the user enters an invalid input. The ordered item is added to the order list.

### Continue Ordering
The user is asked if they would like to continue ordering (Y or N). The following outputs are displayed based on the user input:
* User enters 'Y' or 'y' - The category menu is displayed again requesting the user to make a choice
* User enters 'N' or 'n' - The user is thanked for his order and is displayed a table of the order that is being prepared for them.
* An error message 'Please try again since the typed input was invalid' is displayed if an input other than 'Y', 'y', 'N' or 'n' was entered.

### Receipt
The user is displayed a final receipt with the total cost.