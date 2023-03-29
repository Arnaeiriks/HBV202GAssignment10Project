# Simple Stack Implementation for Integer Numbers

This is a Maven project that provides a simple implementation of a stack for storing integer numbers, along with some
sample usage and JUnit4 test cases.

# Project Structure

The project follows the standard Maven project structure, which is as follows:

- `src/main/java`: Contains the implementation of a simple stack and a ´main´ method for demonstrating some simple
  usage.
    - `IntStack.java`: Implementation of a simple stack.
    - `IntStackMain.java`: A class with a main method demonstrating some sample usage of the stack.

- `src/test/java`: Contains the JUnit4 test cases for the simple stack implementation
    - `IntStackTest.java`: A skeleton for a class containing JUnit4 test cases for the `IntStack` class, containing one
      sample test case.

# Maven Commands

The following Maven commands are available for this project:

- `mvn compile`: Compiles all implementation classes.
- `mvn exec:java`: Executes the main method of the implementation.
- `mvn test`: Runs all test cases (i.e. all classes with a name that either starts with `Test` or ends with `Test`
  , `Tests`, or `TestCase`).

# Running the Project

To run the simple usage of the stack implementation execute the following command:

`mvn exec:java`

# Testing the project

To run the JUnit4 test cases for stack implementation, execute the following command:

`mvn test`

# License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

# Design

See [Design](path/to/design.md) for details about the design.

# Additional Information

- Maven supports executing the `main` method of the implementation using the `exec:java command. This is useful for
  testing the implementation manually.
- The JUnit4 test cases are located in the `src/test/java` directory and are automatically executed when running
  the `maven test` command.
- The `IntStackTest.java` file contains a skeleton for a class containing the JUnit4 test cases for the IntStack class.
  You can add more test cases to this class to test your implementation further.


