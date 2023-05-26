# Calculator-Using-CSharp

The Calculator using C# is a console application that demonstrates the usage of the Strategy design pattern to perform different arithmetic operations. The program allows users to perform addition and multiplication operations on two numbers using different strategies.

## Code Overview
The provided code snippet includes the following components:

User Information: The program displays the student's name and Humber ID.

Calculator Initialization: An instance of the Calculator class is created, which serves as the context for performing calculations.

Addition Calculation: The program creates an instance of the AddStrategy class, representing the addition strategy. The strategy object is then assigned to the calculator context using the SetStrategy method. The Calculate method is called with two numbers (65 and 75) to perform the addition operation, and the result is displayed.

Multiplication Calculation: Similarly, the program creates an instance of the MultiplyStrategy class, representing the multiplication strategy. The strategy object is assigned to the calculator context, and the Calculate method is called with the same two numbers to perform the multiplication operation. The result is displayed.

## Usage
To use the Calculator using C#, follow these steps:

Ensure that the necessary dependencies are included and the required classes (Calculator, IStrategy, AddStrategy, MultiplyStrategy) are available.

Run the code in a console application environment.

The program will display the student's name and Humber ID.

The program will create an instance of the Calculator class.

An addition strategy (AddStrategy) is created and assigned to the calculator context using the SetStrategy method.

The Calculate method is called with two numbers, and the result of the addition operation is displayed.

A multiplication strategy (MultiplyStrategy) is created and assigned to the calculator context.

The Calculate method is called again with the same two numbers, and the result of the multiplication operation is displayed.

The program terminates after displaying the results.

## Notes
Please note that the provided code snippet is a simplified implementation of the Calculator using C#. In a real-world scenario, additional functionalities and operations may be implemented, and multiple strategies for various arithmetic operations can be utilized within the calculator context.
