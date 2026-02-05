# Number-System-
This project is developed using the C programming language.

The main purpose of this program is to perform various string operations.

The program is menu-driven, which makes it user-friendly.

It allows the user to enter a string only once or multiple times.

The program uses functions to divide tasks clearly.

Each function performs a specific string operation.

This improves readability and maintainability of the code.

The header file <stdio.h> is used for standard input and output.

The header file <string.h> is used for string handling functions.

The header file <conio.h> is used for getch() function.

Function prototypes are declared before main() function.

This helps the compiler to know about functions in advance.

The execution of the program starts from the main() function.

The main() function calls inputString() to begin the program.

The inputString() function is responsible for taking user input.

A character array of size 40 is declared to store the string.

A welcome message is displayed to the user.

The user is prompted to enter a string.

The fgets() function is used to read the string safely.

This avoids buffer overflow problems.

The newline character added by fgets() is removed.

strcspn() function is used for this purpose.

The entered string is displayed back to the user.

The string is passed to the MainMenu() function.

MainMenu() receives the string using a character pointer.

The pointer allows modification of the original string.

The menu is displayed with different string operation options.

The menu contains seven different operations.

The user selects an option using the keyboard.

getch() is used to capture the choice instantly.

Option 1 converts the string into uppercase letters.

Option 2 converts the string into lowercase letters.

Option 3 reverses the complete string.

Option 4 reverses each word at its original position.

Option 5 converts the first letter of each word to uppercase.

Option 6 converts the last letter of each word to uppercase.

Option 7 counts the occurrence of each character.

Based on the choice, the respective function is called.

Conditional statements (if-else) are used for selection.

After performing the operation, the result is displayed.

The user is then asked whether to continue with the same string.

Pressing s repeats the menu with the same string.

Pressing n allows the user to enter a new string.

This provides flexibility to the user.

The convertUpperCase() function changes lowercase letters to uppercase.

It checks each character using a loop.

ASCII value comparison is used to identify lowercase letters.

A value of 32 is subtracted to convert to uppercase.

The modified string is printed.

getch() pauses the output.

The convertLowerCase() function converts uppercase letters to lowercase.

It also uses ASCII value logic.

Each uppercase character is increased by 32.

Characters other than alphabets are ignored.

The updated string is displayed on the screen.

The reverseString() function prints the string in reverse order.

It uses strlen() to find the length of the string.

A loop prints characters from last index to first.

The original string remains unchanged.

This function only affects output.

The firstLetterWordUpperCase() function capitalizes the first letter of each word.

It checks if the character is at index 0.

It also checks if the previous character is a space.

Only lowercase letters are converted.

This improves sentence formatting.

The updated string is printed.

The lastLetterWordUpperCase() function capitalizes the last letter of each word.

It checks if the next character is a space or null character.

This ensures correct identification of word endings.

Only lowercase letters are converted to uppercase.

The countOccurance() function counts character frequency.

A temporary array is used to store counted characters.

This prevents repeated counting of the same character.

Nested loops are used for comparison.

A found flag is used to detect duplicates.

Each unique character’s count is printed.

Spaces are also counted if present.

This function demonstrates array and loop usage.

The reverseOnPosition() function reverses words individually.

Word order remains unchanged.

A temporary array stores characters of one word.

When a space is detected, the word is reversed.

The reversed word is copied back to the original string.

This process repeats for all words.

The final string is displayed.

The program uses null-terminated strings.

Pointer passing avoids unnecessary copying of data.

Functions modify the same string efficiently.

The program avoids global variables.

This makes the code safer.

The program demonstrates modular programming.

Each function has a single responsibility.

The menu system improves user interaction.

The program uses loops effectively.

Conditional statements control the flow.

It demonstrates real-world string manipulation.

The code is easy to debug and extend.

Input size is limited for safety.

The program follows structured programming principles.

It is suitable for beginners.

The project helps understand ASCII values.

It improves understanding of character arrays.

The use of fgets() is safer than gets().

The program supports sentence input with spaces.

It handles multiple operations without restarting.

User choices are processed efficiently.

The program demonstrates pointer usage clearly.

It shows practical application of loops.

It helps in learning menu-based programs.

It is ideal for academic projects.

The code works well in Turbo C environment.

Minor changes are needed for GCC compiler.

conio.h functions are compiler dependent.

Output is clean and readable.

The program is interactive.

Each function pauses before returning.

This allows the user to read output properly.

The project strengthens logic building skills.

It enhances understanding of strings.

It demonstrates function calling.

The program avoids unnecessary memory usage.

It uses static arrays for simplicity.

No dynamic memory allocation is used.

This makes it beginner-friendly.

The program uses standard C syntax.

It avoids complex library functions.

Most logic is implemented manually.

This improves learning outcomes.

The project can be extended further.

New string operations can be added easily.

The menu can be expanded.

Error handling can be improved.

Case sensitivity handling is clear.

The program encourages good coding practices.

It uses meaningful function names.

It separates input, processing, and output.

The program is suitable for viva explanation.

Each function can be explained independently.

The logic is straightforward.

The program is well structured.

It demonstrates the power of functions.

It shows reuse of code.

It avoids redundant logic.

The project is easy to understand.

It helps in mastering strings.

It teaches menu-driven programming.

It strengthens C fundamentals.

It uses both arrays and pointers.

It is a complete mini project.

It is useful for practical exams.

The program can run continuously.

User has full control over execution.

It supports both uppercase and lowercase strings.

It maintains word positions correctly.

It handles spaces efficiently.

It produces correct output consistently.

It demonstrates logical thinking.

It follows procedural programming model.

It avoids unnecessary complexity.

It is well suited for students.

The code can be reused in other projects.

It is adaptable to different inputs.

It improves coding confidence.

It encourages modular design.

It is easy to enhance.

It teaches debugging skills.

It is logically sound.

It improves problem-solving ability.

It demonstrates real-life string operations.

It is a strong foundation project.

The project can be documented easily.

It can be converted into report format.

It supports interactive learning.

It reinforces core C concepts.

It is suitable for first-year students.

It demonstrates clean coding style.

It avoids unsafe functions.

It uses meaningful logic.

It is a complete C program.

It fulfills academic requirements.

The project is well organized.

It covers multiple string concepts.

It improves understanding of character manipulation.

It demonstrates use of ASCII values.

It shows real-time user interaction.

It uses simple and clear logic.

It is easy to explain to examiners.

It is suitable for lab records.

It improves practical knowledge.

It demonstrates programming discipline.

The project is reliable.

It is efficient for small inputs.

It demonstrates structured programming.

It encourages best practices.

It strengthens fundamentals of C.

It is a complete learning package.

It builds confidence in string handling.

It is ideal for demonstrations.

It is easy to understand and implement.

Overall, this is a complete and effective C String Operation Project. 
