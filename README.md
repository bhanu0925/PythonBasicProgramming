**PythonBasicProgramming_ 11**

1. Write a Python program to find words which are greater than given length k?
2. Write a Python program for removing i-th character from a string?
3. Write a Python program to split and join a string?
4. Write a Python to check if a given string is binary string or not?
5. Write a Python program to find uncommon words from two Strings?
6. Write a Python to find all duplicate characters in string?
7. Write a Python Program to check if a string contains any special character?

**PythonBasicProgramming_ 12**
1. Write a Python program to Extract Unique values dictionary values?
2. Write a Python program to find the sum of all items in a dictionary?
3. Write a Python program to Merging two Dictionaries?
4. Write a Python program to convert key-values list to flat dictionary?
5. Write a Python program to insertion at the beginning in OrderedDict?
6. Write a Python program to check order of character in string using OrderedDict()?
7. Write a Python program to sort Python Dictionaries by Key or Value?

**PythonBasicProgramming_13**

Question 1:
Write a program that calculates and prints the value according to the given formula:
Q = Square root of [(2 * C * D)/H]
Following are the fixed values of C and H:
C is 50. H is 30.
D is the variable whose values should be input to your program in a comma-separated
sequence.
Example
Let us assume the following comma separated input sequence is given to the program:
100,150,180
The output of the program should be:
18,22,24

Question 2:
Write a program which takes 2 digits, X,Y as input and generates a 2-dimensional array. The
element value in the i-th row and j-th column of the array should be i*j.
Note: i=0,1.., X-1; j=0,1,¡Y-1.
Example
Suppose the following inputs are given to the program:
3,5
Then, the output of the program should be:
[[0, 0, 0, 0, 0], [0, 1, 2, 3, 4], [0, 2, 4, 6, 8]]

Question 3:
Write a program that accepts a comma separated sequence of words as input and prints the
words in a comma-separated sequence after sorting them alphabetically.
Suppose the following input is supplied to the program:
without,hello,bag,world
Then, the output should be:
bag,hello,without,world

Question 4:
Write a program that accepts a sequence of whitespace separated words as input and prints
the words after removing all duplicate words and sorting them alphanumerically.
Suppose the following input is supplied to the program:
hello world and practice makes perfect and hello world again
Then, the output should be:
again and hello makes perfect practice world

Question 5:
Write a program that accepts a sentence and calculate the number of letters and digits.
Suppose the following input is supplied to the program:
hello world! 123
Then, the output should be:
LETTERS 10

DIGITS 3

Question 6:
A website requires the users to input username and password to register. Write a program to
check the validity of password input by users.
Following are the criteria for checking the password:
1. At least 1 letter between [a-z]
2. At least 1 number between [0-9]
1. At least 1 letter between [A-Z]
3. At least 1 character from [$#@]
4. Minimum length of transaction password: 6
5. Maximum length of transaction password: 12
Your program should accept a sequence of comma separated passwords and will check them
according to the above criteria. Passwords that match the criteria are to be printed, each
separated by a comma.
Example
If the following passwords are given as input to the program:
ABd1234@1,a F1#,2w3E*,2We3345
Then, the output of the program should be:
ABd1234@1

**PythonBasicProgramming_14**

Question 1:
Define a class with a generator which can iterate the numbers, which are divisible by
7, between a given range 0 and n.

Question 2:
Write a program to compute the frequency of the words from the input. The output
should output after sorting the key alphanumerically.
Suppose the following input is supplied to the program:
New to Python or choosing between Python 2 and Python 3? Read Python 2 or
Python 3.
Then, the output should be:
2:2
3.:1
3?:1
New:1
Python:5
Read:1
and:1
between:1
choosing:1
or:2
to:1

Question 3:

Define a class Person and its two child classes: Male and Female. All classes have a
method &quot;getGender&quot; which can print &quot;Male&quot; for Male class and &quot;Female&quot; for Female
class.

Question 4:
Please write a program to generate all sentences where subject is in [&quot;I&quot;, &quot;You&quot;] and
verb is in [&quot;Play&quot;, &quot;Love&quot;] and the object is in [&quot;Hockey&quot;,&quot;Football&quot;].

Question 5:
Please write a program to compress and decompress the string &quot;hello world!hello
world!hello world!hello world!&quot;.

Question 6:
Please write a binary search function which searches an item in a sorted list. The
function should return the index of element to be searched in the list.

**PythonBasicProgramming_15**

Question 1:
Please write a program using generator to print the numbers which can be divisible by 5 and
7 between 0 and n in comma separated form while n is input by console.
Example:
If the following n is given as input to the program:
100
Then, the output of the program should be:
0,35,70

Question 2:
Please write a program using generator to print the even numbers between 0 and n in comma
separated form while n is input by console.
Example:
If the following n is given as input to the program:
10
Then, the output of the program should be:
0,2,4,6,8,10

Question 3:
The Fibonacci Sequence is computed based on the following formula:
f(n)=0 if n=0
f(n)=1 if n=1
f(n)=f(n-1)+f(n-2) if n&gt;1
Please write a program using list comprehension to print the Fibonacci Sequence in comma
separated form with a given n input by console.
Example:
If the following n is given as input to the program:
7

Then, the output of the program should be:
0,1,1,2,3,5,8,13

Question 4:
Assuming that we have some email addresses in the &quot;username@companyname.com&quot; format,
please write program to print the user name of a given email address. Both user names and
company names are composed of letters only.
Example:
If the following email address is given as input to the program:
john@google.com
Then, the output of the program should be:
john

Question 5:
Define a class named Shape and its subclass Square. The Square class has an init function
which takes a length as argument. Both classes have a area function which can print the area
of the shape where Shape&#39;s area is 0 by default.

**PythonBasicProgramming_16**

Question1. Write a function that stutters a word as if someone is struggling to read it. The
first two letters are repeated twice with an ellipsis ... and space after each, and then the
word is pronounced with a question mark ?.
Examples
stutter(&quot;incredible&quot;) ➞ &quot;in... in... incredible?&quot;
stutter(&quot;enthusiastic&quot;) ➞ &quot;en... en... enthusiastic?&quot;
stutter(&quot;outstanding&quot;) ➞ &quot;ou... ou... outstanding?&quot;

Hint :- Assume all input is in lower case and at least two characters long.

Question 2.Create a function that takes an angle in radians and returns the corresponding
angle in degrees rounded to one decimal place.
Examples
radians_to_degrees(1) ➞ 57.3
radians_to_degrees(20) ➞ 1145.9
radians_to_degrees(50) ➞ 2864.8

Question 3. In this challenge, establish if a given integer num is a Curzon number. If 1 plus
2 elevated to num is exactly divisible by 1 plus 2 multiplied by num, then num is a Curzon
number.
Given a non-negative integer num, implement a function that returns True if num is a Curzon
number, or False otherwise.
Examples
is_curzon(5) ➞ True
2 ** 5 + 1 = 33
2 * 5 + 1 = 11
33 is a multiple of 11
is_curzon(10) ➞ False
2 ** 10 + 1 = 1025
2 * 10 + 1 = 21
1025 is not a multiple of 21
is_curzon(14) ➞ True
2 ** 14 + 1 = 16385
2 * 14 + 1 = 29
16385 is a multiple of 29

Question 4.Given the side length x find the area of a hexagon.

Examples
area_of_hexagon(1) ➞ 2.6
area_of_hexagon(2) ➞ 10.4
area_of_hexagon(3) ➞ 23.4

Question 5. Create a function that returns a base-2 (binary) representation of a base-10
(decimal) string number. To convert is simple: ((2) means base-2 and (10) means base-10)
010101001(2) = 1 + 8 + 32 + 128.
Going from right to left, the value of the most right bit is 1, now from that every bit to the left
will be x2 the value, value of an 8 bit binary numbers are (256, 128, 64, 32, 16, 8, 4, 2, 1).
Examples
binary(1) ➞ &quot;1&quot;
1*1 = 1
binary(5) ➞ &quot;101&quot;
1*1 + 1*4 = 5
binary(10) ➞ &quot;1010&quot;
1*2 + 1*8 = 10

**PythonBasicProgramming_17**

Question1. Create a function that takes three arguments a, b, c and returns the sum of the
numbers that are evenly divided by c from the range a, b inclusive.
Examples
evenly_divisible(1, 10, 20) ➞ 0
No number between 1 and 10 can be evenly divided by 20.
evenly_divisible(1, 10, 2) ➞ 30
2 + 4 + 6 + 8 + 10 = 30
evenly_divisible(1, 10, 3) ➞ 18
 3 + 6 + 9 = 18

Question2. Create a function that returns True if a given inequality expression is correct and
False otherwise.
Examples
correct_signs(&quot;3 &lt; 7 &lt; 11&quot;) ➞ True
correct_signs(&quot;13 &gt; 44 &gt; 33 &gt; 1&quot;) ➞ False
correct_signs(&quot;1 &lt; 2 &lt; 6 &lt; 9 &gt; 3&quot;) ➞ True

Question3. Create a function that replaces all the vowels in a string with a specified character.
Examples
replace_vowels(&quot;the aardvark&quot;, &quot;#&quot;) ➞ &quot;th# ##rdv#rk&quot;
replace_vowels(&quot;minnie mouse&quot;, &quot;?&quot;) ➞ &quot;m?nn?? m??s?&quot;
replace_vowels(&quot;shakespeare&quot;, &quot;*&quot;) ➞ &quot;sh*k*sp**r*&quot;

Question4. Write a function that calculates the factorial of a number recursively.
Examples
factorial(5) ➞ 120
factorial(3) ➞ 6
factorial(1) ➞ 1
factorial(0) ➞ 1

Question 5
Hamming distance is the number of characters that differ between two strings.
To illustrate:
String1: &quot;abcbba&quot;
String2: &quot;abcbda&quot;
Hamming Distance: 1 - &quot;b&quot; vs. &quot;d&quot; is the only difference.
Create a function that computes the hamming distance between two strings.
Examples
hamming_distance(&quot;abcde&quot;, &quot;bcdef&quot;) ➞ 5
hamming_distance(&quot;abcde&quot;, &quot;abcde&quot;) ➞ 0
hamming_distance(&quot;strong&quot;, &quot;strung&quot;) ➞ 1

**PythonBasicProgramming_18**

Question 2
The &quot;Reverser&quot; takes a string as input and returns that string in reverse order, with the
opposite case.
Examples
reverse(&quot;Hello World&quot;) ➞ &quot;DLROw OLLEh&quot;
reverse(&quot;ReVeRsE&quot;) ➞ &quot;eSrEvEr&quot;
reverse(&quot;Radar&quot;) ➞ &quot;RADAr&quot;

Question 3
You can assign variables from lists like this:
lst = [1, 2, 3, 4, 5, 6]
first = lst[0]
middle = lst[1:-1]
last = lst[-1]
print(first) ➞ outputs 1
print(middle) ➞ outputs [2, 3, 4, 5]
print(last) ➞ outputs 6
With Python 3, you can assign variables from lists in a much more succinct way. Create
variables first, middle and last from the given list using destructuring assignment
(check the Resources tab for some examples), where:
first ➞ 1
middle ➞ [2, 3, 4, 5]
last ➞ 6

Your task is to unpack the list writeyourcodehere into three variables, being first,
middle, and last, with middle being everything in between the first and last element. Then
print all three variables.

Question 4
Write a function that calculates the factorial of a number recursively.
Examples
factorial(5) ➞ 120
factorial(3) ➞ 6
factorial(1) ➞ 1
factorial(0) ➞ 1

Question 5
Write a function that moves all elements of one type to the end of the list.
Examples
move_to_end([1, 3, 2, 4, 4, 1], 1) ➞ [3, 2, 4, 4, 1, 1]
 Move all the 1s to the end of the array.
move_to_end([7, 8, 9, 1, 2, 3, 4], 9) ➞ [7, 8, 1, 2, 3, 4, 9]
move_to_end([&quot;a&quot;, &quot;a&quot;, &quot;a&quot;, &quot;b&quot;], &quot;a&quot;) ➞ [&quot;b&quot;, &quot;a&quot;, &quot;a&quot;, &quot;a&quot;]

**PythonBasicProgramming_19**

Question1
Create a function that takes a string and returns a string in which each character is repeated
once.
Examples
double_char(&quot;String&quot;) ➞ &quot;SSttrriinngg&quot;
double_char(&quot;Hello World!&quot;) ➞ &quot;HHeelllloo WWoorrlldd!!&quot;
double_char(&quot;1234!_ &quot;) ➞ &quot;11223344!!__ &quot;

Question2
Create a function that reverses a boolean value and returns the string &quot;boolean expected&quot;
if another variable type is given.
Examples
reverse(True) ➞ False
reverse(False) ➞ True
reverse(0) ➞ &quot;boolean expected&quot;
reverse(None) ➞ &quot;boolean expected&quot;

Question3
Create a function that returns the thickness (in meters) of a piece of paper after folding it n
number of times. The paper starts off with a thickness of 0.5mm.
Examples
num_layers(1) ➞ &quot;0.001m&quot;
Paper folded once is 1mm (equal to 0.001m)
num_layers(4) ➞ &quot;0.008m&quot;
Paper folded 4 times is 8mm (equal to 0.008m)
num_layers(21) ➞ &quot;1048.576m&quot;
Paper folded 21 times is 1048576mm (equal to 1048.576m)

Question4

Create a function that takes a single string as argument and returns an ordered list containing
the indices of all capital letters in the string.
Examples
index_of_caps(&quot;eDaBiT&quot;) ➞ [1, 3, 5]
index_of_caps(&quot;eQuINoX&quot;) ➞ [1, 3, 4, 6]
index_of_caps(&quot;determine&quot;) ➞ []
index_of_caps(&quot;STRIKE&quot;) ➞ [0, 1, 2, 3, 4, 5]
index_of_caps(&quot;sUn&quot;) ➞ [1]

Question5
Using list comprehensions, create a function that finds all even numbers from 1 to the given
number.
Examples
find_even_nums(8) ➞ [2, 4, 6, 8]
find_even_nums(4) ➞ [2, 4]
find_even_nums(2) ➞ [2]
