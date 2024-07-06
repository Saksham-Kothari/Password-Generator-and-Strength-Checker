# Sk's Password Services

Welcome to Sk's Password Services! This project is a comprehensive password management application designed to generate and evaluate the strength of passwords, ensuring that users can create secure and robust passwords for their needs.

## Features
- **Password Generation**: Generate passwords with customizable criteria including uppercase letters, lowercase letters, numbers, and special characters.
- **Password Strength Check**: Evaluate the strength of existing passwords and receive feedback on how to improve them.
- **Useful Information**: Get guidelines and best practices for creating strong passwords.

## Project Structure

- **Main.java**: Entry point of the application.
- **Alphabet.java**: Defines the character sets used for password generation.
- **Generator.java**: Handles the main logic for password generation and evaluation.
- **GeneratorTest.java**: Contains unit tests for the `Generator` and `Alphabet` classes.
- **Password.java**: Represents a password and includes methods to calculate its strength.

## Usage

### Running the Application
1. Clone the repository.
2. Compile the Java files:
    ```bash
    javac Main.java Alphabet.java Generator.java Password.java
    ```
3. Run the application:
    ```bash
    java Main
    ```

### Password Generator
1. Select option `1` to generate a new password.
2. Answer the prompts to specify which character types to include in the password.
3. Enter the desired length of the password.
4. The generated password will be displayed.

### Password Strength Check
1. Select option `2` to check the strength of an existing password.
2. Enter your password when prompted.
3. The application will display the strength of the password and provide feedback.

### Useful Information
- Select option `3` to view guidelines and best practices for creating strong passwords.

### Exit
- Select option `4` to quit the application.

## Example

### Main Menu
```
Welcome to Sk's Password Services :)
Enter 1 - Password Generator
Enter 2 - Password Strength Check
Enter 3 - Useful Information
Enter 4 - Quit
Choice: 
```

## Contributing
Feel free to fork this repository and contribute by submitting pull requests. Ensure that all changes are well-documented and tested.

## License
This project is licensed under the MIT License.

---

Enjoy using Sk's Password Services! Your feedback and contributions are welcome to improve the application further.
