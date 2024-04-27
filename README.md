# Logical-Calculator-with-c-and-Proteus
This project involves interfacing an LCD and a Keypad with an 8051 microcontroller. The objective is to develop a program that facilitates the input of two 16-bit hexadecimal numbers from the keypad (ranging from 0000 to FFFF). After input, the user is prompted to select one of the logical operations: AND, OR, XOR, or NOR. Subsequently, the program computes the result of the selected operation and displays it on the LCD in both binary and hexadecimal formats.

To input hexadecimal numbers using the keypad, the following mapping is employed:


'/' key: digit A,
'*' key: digit B,
'-' key: digit C,
'+' key: digit D,
'=' key: digit E

'ON/C' key: digit F
The output sequence of the program is structured as follows:

Step 1:
Display Number1=AB75 on the first line and Number2=E27F on the second line of the LCD.
(Clear the LCD)

Step 2:
Prompt the user to select an operator (Displayed on the first line of the LCD).
(Clear the LCD after 2 seconds)

Step 3:
Display the options for logical operations (AND, OR, XOR, NOR) on the first line, and their corresponding numbers on the second line of the LCD.

Step 4:
After the user's selection, display the computed result in both binary and hexadecimal formats on the first and second lines of the LCD, respectively.





