
 <h3>String</h3>
                     We can access a string using indexing. In a string each character is assigned with a unique index value which starts from 0. A string can be written in both single quotes and double quotes.
Example  :  'Hello World'<br>
"Hello World"<br><br>
Program:<br><br>
<img src="images/img1.PNG"><br><br>
Output:<br><br>
Hello<br>
Hello<br><br>
Program<br><br>
<img src="images/img2.PNG"><br><br>
Output<br><br>
Hello<br><br>
Program<br><br>
<img src="images/img3.PNG"><br><br>
Output<br><br>
Lorem ipsum dolor sit amet,<br>
consectetur adipiscing elit,<br>
sed do eiusmod tempor incididunt<br>
ut labore et dolore magna aliqua.<br><br>

Python allows negative indexing as well.<br>
Example : -1, -3, -5.<br>
Where -1 refers to the last index, -2 refers to second last index and so on.<br>
Printing here can be done by placing the string in single or double quotes after print.<br>
<br>
print("Hello World")<br><br>

<h4>Concatenation</h4>
A string in python is immutable i.e. it can not be changed once defined. But concatenation is still possible<br><br>
Program<br><br>
<img src="images/img4.PNG"><br><br>
Output<br><br>
Hello WorldExample<br><br>
Using Join() method also we can concatenate string<br><br>
Program<br><br>
<img src="images/img5.PNG"><br><br>
Output<br><br>
HelloWorld<br><br>
Program<br><br>
<img src="images/img6.PNG"><br><br>
Output<br><br>
HelloWorld<br><br>
<h4>Repetition</h4>This is a unique property of strings in Python programming language. When a string is multiplied with an integer, the characters of string are multiplied the same number of times.<br><br>

Syntax : string * integer<br><br>

Program<br><br>
<img src="images/img7.PNG"><br><br>
Solution<br><br>
kkkkk<br><br>
<h4>Slicing</h4>Slicing is done in Python to select or display the desired number of characters in a string. It is done with the help of symbol ':'<br><br>
Syntax : String[ index: ]<br><br>
Program<br><br>
<img src = "images/img8.PNG"><br><br>
Solution<br><br>
llo World<br><br>
All the characters from and after second index is selected<br><br>
Program<br><br>
<img src = "images/img9.PNG"><br><br>
Solution<br><br>
ello Wo<br><br>
Characters between index number 1 and 8 are selected<br><br>
Length of a string can be calculated using the len function.<br><br>
Syntax : len("string")<br>
len("Hello World"<br>
It will return 11.<br><br>
Deleting / updating from a String:<br><br>
In Python, Updation or deletion of characters from a String is not allowed. This will cause an error because item assignment or item deletion from a String is not supported<br><br>
Program<br><br>
<img src = "images/img10.PNG"><br><br>
Output<br><br>
Initial String:<br>
Hello, I'm a coder<br>
Traceback (most recent call last):<br>
  File "e:\VLAB\python\programs\a.py", line 51, in <module><br>
    String1[2] = 'p'<br>
TypeError: 'str' object does not support item assignment
