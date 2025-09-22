📖 Project Explanation

CalculatorApplication1 is a simple Java console application that works as a basic calculator.
It is designed for beginners who want to strengthen their understanding of Java programming concepts through a practical, real-world example.


---

🔎 What this project does

Displays a menu-driven interface where users can choose an operation.

Performs the following operations:

1. Addition


2. Subtraction


3. Multiplication


4. Division (with division by zero handling)


5. Exit option to close the program.



Reads input safely using the Scanner class.

Ensures invalid inputs (like text or symbols instead of numbers) are caught and handled gracefully.

Loops continuously so the user can perform multiple operations until they decide to exit.



---

🏗 How it works internally

1. Main Loop

The program runs inside a while(true) loop to continuously show the menu.



2. Menu Selection

The user enters a number (1–5). A switch-case structure determines which operation to perform.



3. Performing Operations

Each mathematical operation (add, subtract, multiply, divide) is written as a separate method, keeping the code clean and modular.



4. Error Handling

If the user enters something that’s not a number, the program shows an error message and asks again.

If the user tries to divide by zero, it throws an ArithmeticException and displays an error message.



5. Exiting

When the user chooses option 5, the program prints a thank-you message and terminates.





---

🎯 Learning Objectives

This project helps beginners understand:

Loops → keeping the program running until the user exits.

Switch-case → choosing an operation based on user input.

Methods → breaking down tasks into smaller, reusable functions.

Exception handling → preventing crashes due to invalid input or division by zero.

Clean coding practices → writing modular and readable code.



---

💡 Why this project is important

It’s simple but practical — everyone knows how a calculator works.

It builds a strong base for moving towards advanced projects like a GUI-based calculator using Swing/JavaFX.

It demonstrates how even a small project can showcase good coding practices (input validation, error handling, modularity).
