![Calculator](Images/ex1_1.jpeg)

# Calculator

## What is it?

This project provides a simple calculator that performs basic mathematical operations such as:

- Addition
- Subtraction
- Multiplication
- Division

It was developed for introductory test automation and educational purposes.

## Installation

The link to the .zip of the file can be found [here](https://elearning.fh-joanneum.at/pluginfile.php/115269/mod_folder/content/0/Calculator-Example.zip?forcedownload=1) or in the Configuration Management course on the [E-Learning Website of FH JOANNEUM](https://elearning.fh-joanneum.at/).

## Usage

1. Create a main and import the calculator using `ICalculator calculator = new CalculatorImpl();`
2. Create a new double, name it, choose which mathmatical operation you want to use and also the numbers you want to use in that operation, like this:

    - `double addition = calculator.add(18, 3);`
    - `double subtraction = calculator.minus(10, 7);`
    - `double multiplication = calculator.multiply(3, 18);`
    - `double division = calculator.divide(16, 4);`

3. Now write a `System.out.println:()` with the name of the double in it.
4. Compile the file with `javac`
5. Execute the file with `java`

## Additional Features

The divide method throws a Arithmedic Exception when the Division isn't possible.

## Author

The author of this READ ME is **Ramona Enzi**. For further questions you can reach me at: ramona.enzi@edu.fh-joanneum.at.

Here is also the Link to my [Hithub](https://github.com/monaenzi).