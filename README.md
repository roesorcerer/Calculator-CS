# Calculator Program Readme

This readme file provides an overview of the "Calculator" program, including its purpose, functionality, and usage instructions. The program is designed to perform basic arithmetic calculations such as addition, subtraction, multiplication, and division using two whole numbers provided by the user.

## Program Overview

The "Calculator" program is a C# console application that allows users to perform arithmetic calculations on two whole numbers. It provides a simple and interactive menu-driven interface for selecting the desired calculation and inputting the numbers. The program includes error handling to prevent division by zero and guides the user through the calculation process.

## Program Structure

The program consists of a single C# class named `Calculator` that contains the following key components:

1. **Main Method**: The `Main` method serves as the entry point of the program. It handles exceptions and initiates the `MainMenu` method for calculation.

2. **MainMenu Method**: The `MainMenu` method is responsible for displaying the program's menu, collecting user input for two whole numbers, and performing the selected arithmetic operation. It uses a while loop to keep the program running until the user decides to exit. Key features of the `MainMenu` method include:
   - User input for two whole numbers.
   - A menu to select the desired arithmetic operation (addition, subtraction, multiplication, or division).
   - A switch statement to perform the selected operation and display the result.
   - Error handling to prevent division by zero.
   - An option to retry in case of an incorrect menu choice.

## Getting Started

To use the "Calculator" program, follow these steps:

1. Ensure you have the .NET SDK installed on your computer.

2. Clone or download the code repository containing the `Calculator` class.

3. Open the project in a C# development environment such as Visual Studio or Visual Studio Code.

4. Build and run the program.

5. Follow the on-screen instructions to input two whole numbers and select an arithmetic operation.

6. View the calculation result, and you can perform additional calculations as needed.

## Error Handling

The program includes error handling to handle the following scenarios:

- Division by zero: If the user attempts to divide by zero, a `DivideByZeroException` is caught, and an error message is displayed. The program does not crash and continues to run.

- Invalid menu choices: If the user selects a menu option that is not in the range of 1 to 4, an error message is displayed, and the user can retry.

## Conclusion

The "Calculator" program is a simple yet functional C# console application for performing basic arithmetic calculations. It provides an interactive and user-friendly interface, error handling, and flexibility to perform multiple calculations. Enjoy using the program for your arithmetic needs!
