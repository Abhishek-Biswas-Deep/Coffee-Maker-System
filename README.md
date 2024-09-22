<img src="https://github.com/user-attachments/assets/2ad86f70-12b4-4500-997d-9f8c1874a9b5" alt="Dal logo" width="80"/>
<h1>Associated with Dalhousie University</h1>

## CSCI 1110

## Coffee-Maker-System
**Project Description-**
The program simulates a coffee making system, including coffee beans, a coffee grinder, and a coffee maker. It demonstrates the use of classes, objects, and their interactions in Java.

**Features-**

1. CoffeeBeans class to represent different types of coffee beans.
2. CoffeeGrinder class to grind coffee beans.
3. CoffeeMaker class to brew coffee.
4. Interactive system to manage coffee making process.

**Components-**
1. CoffeeBeans Class
- Represents coffee beans with properties like brand, blend, roast type, and ground state.
- Includes an enum for Roast types: LIGHT, MEDIUM, MEDIUM_DARK, DARK.

2. CoffeeGrinder Class
- Grinds whole coffee beans.

3. CoffeeMaker Class

- Manages the coffee making process.
- Interacts with CoffeeBeans and CoffeeGrinder.
- Controls water level, power state, and brewing process.

4. HumanMakeCoffee Class

- Main class with user interface to interact with the coffee making system.

**How to Run**
1. Clone this repository.
2. Navigate to the project directory.
3. Compile and run the program.

**Input Format-**
The program expects input in the following format:

1. Four sets of coffee bean information (each set on separate lines):
- Brand name
- Blend name
- Roast type (LIGHT, MEDIUM, MEDIUM_DARK, DARK)

2. Menu options (1-4, 0 to exit).
3. Additional inputs based on selected options.

**Usage-**
After inputting coffee bean information, you can:
1. View and select from available coffees
2. View coffee maker status
3. Add water to the coffee maker
4. Brew coffee

**Implementation Details-**
- Uses enums for Roast types
- Demonstrates object-oriented programming concepts

#### Sample Input and Output
Here's an example of how to interact with the program:
##### Input:
```
Kicking Horse
Horse 427
DARK
The Big Lift
Halifax Tour
MEDIUM
Second Cup
Xmas Time
LIGHT
Nespresso
Indonesia
MEDIUM_DARK
1
2
3
1000
2
4
2
0
```
##### Output:
```
Welcome! Please select an option:
Here are your coffee options
(1)
Brand: Kicking Horse
Blend: Horse 427
Roast type: DARK
whole bean
---------
(2)
Brand: The Big Lift
Blend: Halifax Tour
Roast type: MEDIUM
whole bean
---------
(3)
Brand: Second Cup
Blend: Xmas Time
Roast type: LIGHT
whole bean
---------
(4)
Brand: Nespresso
Blend: Indonesia
Roast type: MEDIUM_DARK
whole bean
---------
Make a selection: 1

isOn: true
water left: 0.00
loaded coffee:
Brand: Kicking Horse
Blend: Horse 427
Roast type: DARK
whole bean.

How much water? 1000

isOn: true
water left: 1000.00
loaded coffee:
Brand: Kicking Horse
Blend: Horse 427
Roast type: DARK
whole bean.

How many cups? 2
Brewing coffee...
```
