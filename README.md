Download Link: https://assignmentchef.com/product/solved-program-that-collects-the-statistics-of-word-number-and-character-usage
<br>
Objectives: Refresh C/C++ programming skills. Use C++ I/O streams, string class, and STL containers and algorithms. Use makefile to organize and compile programs.

Statement of Work: Implement a program that collects the statistics of word, number, and character usage in a file (redirected as the standard input).

Requirements:

1.Create a subdirectory called proj1.




2.For this project you need to create at least two files: proj1.cpp, and makefile. Both files should be placed in the proj1 directory.




3.The file proj1.cpp should contain the main function, int main(). In the main() function, the program should read the input (from standard input) until it reaches the end, counting the number of times each word, number, and character is used.

◦A word is defined as a sequence of letters (‘a’..’z’ or ‘A’..’Z’).

◦Words are case insensitive (“AA”, “Aa”, “aA”, and “aa” are the same).

◦A number is defined as a sequence of digits (‘0’..’9′).

◦Note that both words and numbers can be of length of 1, that is, contain one letter or one digit, respectively.

◦Different sequences represent different numbers. For example, number “001” is different from number “1”.

◦Words are separated by numbers or other non-letter and non-digit characters.

◦Numbers are separated by words or other non-letter and non-digit characters.

Output specifications: ◦Your program should track the number of times each word, number, and character happens.

◦The program should then output the ten most used characters, the ten most used numbers, and the ten most used words as well as the number of times these characters/numbers/words are used.

◦ Since words are case insensitive, the program only outputs lower case words.

◦The characters, numbers and words should be printed in the descending order based on the number of times they are used.

◦Handling ties: &#x25fe;When two characters occur the same number of times, the character with the smaller ASCII value should be considered as being used more frequently.

&#x25fe;When two words (or numbers) occur the same number of times, the word (or number) that occurs earlier in the input should be considered as being used more frequently.







4.An example executable code of the program is provided to you (see below). You should make the outputs of your program match this sample executable. When printing characters, use ‘t’ for tab and ‘
’ for newline. All other characters should be printed normally.




5.Write a makefile for your project that compiles an executable called proj1.x




6.You are encouraged to use any C++ STL containers and algorithms. You should also use C++ string class instead of default c-strings. Here are a few good reference links for library lookups:

◦C++ STL Containers

◦C++ string class library




7.Your program must be able to compile and run on linprog.




Example executable, some test cases




Download a set of 4 sample test files at this link. This is a tar file containing 4 test files (test0, test1, test2, test3). You will need to unpack this tar file in your project directory.

When you create your own executable, you’ll need to re-direct any test files as the standard input to your program, like this:proj1.x &lt; test0