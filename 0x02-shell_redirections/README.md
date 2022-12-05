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

**head** 
This command is used to display the first 10th lines of a file if no parameter is used. We can set the numbers of line by using the opption -n and the required number. for example to get the first 14 lines the command will be like *head -n 21 <file>*. head is the opposit of **tail**

**Combination of head and tail**
To diaplay the specified line of a text file, we can use both head and tail commands. It is a simple mathematical trick. for example to print the third line:- Firat we have to extract the firat three lines from a text file, (this can be done using head command), then print the last one line using tail command. Example: to print the third line from below text file
		A
		B
		C
		D
		E
head -n 3 <text> --> this prepare A B and c 
then use tain -n 1 <text> but now <text> is a standard output comes from the head command. thus C will be displayed.    head -n 3 <text> | tail -1    **It is just apileline**

**Standard Output**
> is used to write the output to file. If the file is already available it will overwrite the new reult onto the the file. 

**Filters and Standard Output**
One of the filters is tail, which is used to read the last n lines. And it is possible to read a file using tail command and then *Append* or *Overwrite* the tresul onto th same file or onto other file.
for example to append the last line onto the same file
	*tail -n 1 <file_1> >><file_1>

**Special Characters**
* represent any number of character
? represent only one but any character

Let use * in example. To delete files and folders with .js extension   rm -R ./*.js
