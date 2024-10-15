![CoffeeMakerEspressoGIF](https://github.com/user-attachments/assets/b2050178-9e0b-498e-ae7f-2c10d433b5c9)

#<div style=center> Coffee Machine OOP <div>

This project is a simple Object-Oriented Programming (OOP) based coffee machine simulation in Python. It models a coffee machine that prepares various drinks, manages resources (water, milk, coffee), and handles payment transactions.

## Features

- **Resource Management**: Keeps track of available water, milk, and coffee resources using the `CoffeeMaker` class.
- **Resource Report**: Displays current resources and profit.
- **Menu System**: Offers a menu with multiple drink options, each having different ingredient requirements and costs (`Menu` and `MenuItem` classes).
- **Sufficiency Check**: Ensures the machine has enough ingredients to prepare a drink.
- **Payment Handling**: Processes coin inputs and calculates total money received, returning change if necessary (`MoneyMachine` class).
- **Interactive Simulation**: Continuously prompts for user input to order drinks, print reports, or turn off the machine.

## Project Structure

The main classes in the project are:

- **`CoffeeMaker`**: Handles resource tracking and coffee preparation.
- **`MoneyMachine`**: Manages coin input and payment processing.
- **`Menu` and `MenuItem`**: Models the drinks available in the coffee machine, each with its own ingredient requirements and cost.

### Code Structure
- **`menu.py`**: Contains the `Menu` and `MenuItem` classes for modeling the drinks.
- **`coffee_maker.py`**: Contains the `CoffeeMaker` class for managing resources.
- **`money_machine.py`**: Contains the `MoneyMachine` class for handling payments.
- **`main.py`**: The entry point of the program, which runs the simulation.

### Example Drinks:
- **Latte**: Requires 200ml water, 150ml milk, 24g coffee, and costs $2.5.
- **Espresso**: Requires 50ml water, 18g coffee, and costs $1.5.
- **Cappuccino**: Requires 250ml water, 50ml milk, 24g coffee, and costs $3.

## Requirements

- Python 3.x

## How to Run

1. Clone this repository:

    ```bash
    git clone https://github.com/R-Madhavan/Coffee-Machine-OOP.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Coffee-Machine-OOP
    ```

3. Run the main script:

    ```bash
    python main.py
    ```

4. You will be prompted with options to:
   - Order a drink (latte/espresso/cappuccino).
   - Print a report of the current machine resources and profits by typing `report`.
   - Turn off the machine by typing `off`.

## Example Output

```bash
What would you like? (latte/espresso/cappuccino): latte
Please insert coins.
How many quarters?: 10
How many dimes?: 0
How many nickles?: 0
How many pennies?: 0
Here is $0.5 in change.
Here is your latte ☕️. Enjoy!
```
