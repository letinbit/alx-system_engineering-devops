**Standard Output**
#!/bin/bash
echo 'Hello, World'
	the above script is used to print Hello, World onto the default standard out put thart is Display unit.

**Unicode symbols and special characters**
echo \"\($u00da4''o'\)\'   In this script \ is used to let the bash ignore the next character meaning just to consider as literal character. $\U is usedvto use the value of that uncode.


**cat**

It use used to display the whole content of a file or a standard input
*cat <file>*

**Using cat command for more than one fil**
	IT is possible to print the content of two files using cat. here is the command syntax:-
	cat <file_1> <file_2>

**tail**
This command is used to display the last 10th lines of a file if no parameter is used. We can set the numbers of line by using the opption -n and the required number. for example to get the last 21 lines the command will be like tail -n 21 <file>. tail is the opposit of **head**
