1
The error was that the num1 and num2 type were both strings, so the operation to add them would concatenate the strings rather than numerically adding them.

2
When subtracting a number from a string, javascript will automatically convert the string to an int. If we subtract zero from a string, this will simply convert the string to an int (assuming the string is able to be converted) without any change of value. The fix involved subtracting 0 from both num1 and num2, so they could be added as ints, as desired.