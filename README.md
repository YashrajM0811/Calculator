## Calculator Application
This is a Java-based calculator application that provides a graphical user interface (GUI) for users to perform basic arithmetic operations. The application is built using the following components:

## Classes and Objects
Calculator class: This is the main class that implements the ActionListener interface. It contains the necessary methods and variables to create the GUI components, handle user input, and perform calculations.
1. JFrame object: This is the main window of the application that contains all the GUI components.
2. JTextField object: This is the text field where the user can input numbers and view the results.
3. JButton objects: These are the buttons that represent the numbers 0-9, arithmetic operators (+, -, *, /), and other functions (decimal point, equals, delete, clear, and negative).
4. JPanel object: This is the panel that contains the number buttons and function buttons.

## Constructors
The Calculator constructor initializes the GUI components, sets their properties, and adds them to the frame.
## Abstraction Method
The actionPerformed method is an abstraction method that is called when a button is clicked. It determines which button was clicked and performs the corresponding action.

## Inheritance
The Calculator class implements the ActionListener interface, which is a part of the Java AWT package. This interface provides the actionPerformed method that is used to handle events.
## Features
The calculator application provides the following features:
1. Basic arithmetic operations: addition, subtraction, multiplication, and division
2. Decimal point support
3. Equals button to display the result
4. Delete button to delete the last character
5. Clear button to clear the text field
6. Negative button to change the sign of the number

## Running the Application
To run the application, simply compile the Calculator.java file and execute the resulting Calculator.class file. This will launch the GUI calculator application.

## Note: This application is built using Java 8 and the Java AWT package. It is recommended to use a compatible Java version to run the application.