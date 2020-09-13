UI Design Document:
The user interface design consists of a 4x3 design for the numbers from 1-9 in the first three
rows and the last row consists of 0,a decimal point and an “=” sign.
The right side consists of five buttons for Deletion and four mathematical operations such as
addition,subtraction,multiplication and division.
The buttons are designed with touchable opacity such that the user sees the background
when the button is being pressed.
The place where the result text and the input text appears is white and the background for
the operators is black and are aligned at center and the numbers are aligned at center with a
background of blue colour.
All the colours,fonts,alignment are being defined under the Stylesheet.
The return method gives the numbers and operators in the specified style mentioned in the
stylesheet.








Back-end explanation document for Calculator:
I have created a calculator using react-native from scratch.The calculator
comprises of the basic mathematical operation such as addition,subtraction,multiplication
and division.In addition to the numbers,a delete button is also being created.
I have defined the mathematical operators in an array and initially the result text and the
calculation text are initialized as “NULL” .
For evaluating the input given by the user,I have made use of the eval() function that
evaluates by considering the input as a string.
In case if the user presses the “=” sign,it returns the result text by validation if there are two
operands and an operator,else it returns the operand in case of a single operand.
Ex:”2=” ,result=2
I have made use of a switch case to work when the user inputs the operators.
When the user presses the “DEL” button,the text is being split and the last character is being
popped out and again the string is joined and displayed.
When the user gives a string such as “2+” ,it returns null.
The render method gives out the Logic in which the numbers are arranged in rows
accordingly using for loops .The numbers are pushed into an array called rows and are
displayed whereas the operators are pushed into an array called “ops” and displayed
accordingly.
