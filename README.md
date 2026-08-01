# Java Calculator

A simple desktop calculator built with Java Swing, supporting basic arithmetic operations (addition, subtraction, multiplication, division).

## Tech Stack
- Java
- Swing (GUI)

## Setup

1. Clone the repo
   ```bash
   git clone <your-repo-url>
   cd calculator
   ```

2. Compile and run
   ```bash
   javac -d bin src/app/Calculator.java src/module-info.java
   java --module-path bin -m calculator/app.Calculator
   ```

   Or simply open the project in Eclipse (or any Java IDE) and run `Calculator.java` directly.

## Features
- Basic operations: addition, subtraction, multiplication, division
- Clear (CLR) and delete (DEL) buttons
- Decimal point support
