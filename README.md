# Matrix-Object-Oriented-Programming

This is a simple program applying the princples of Object Oriented Programming to a 2 dimensional matrix. The program asks the user 
for the number of rows and coloumns in the matrix on the console and the user returns the answer to these prompts inside the console also.
The first index [0][0] is 0 and subsequent columns are one more then the previous. Each
row is the coloumns of the row above with 10 added to it. 

For example if the user put in 3 for the number of columns and 3 for number of rows you would get a matrix:

0    1    2
10   11   12
20   21   22

Then the user is prompted on what he would like to do to his matrix. Several options are available:

T transpose   - Rows become colums (and vice versa)
C columnSum   - Caclulate the sum of the values in each column
R reverseRows - Reverse all elements in every row of the matrix
P PrintMatrix - This will print the original matrix
AR AddReverse - Add the reverse to your Original Matrix
AN AddNumber  - Add a Number to each value in the Matrix
Q quit        - Exit the program

All of these choices except Q for quiting the program are functions executed from the matrix class which the user created an 
object of in the beginner. After each transformation the user is given this option choice on the console and his/her answer 
should also be on the console. At the end the user should quit the program by typing Q into the console. 

Give it a shot! 
