# Assignment-2-2D-Array-Manipulation-solution

Download Here: [Assignment 2: 2D Array Manipulation solution](https://jarviscodinghub.com/assignment/assignment-2-2d-array-manipulation-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

In this assignment you are to code each of the functions specified below. You will then need to test
them with a main() function that invokes them by producing the same sequence of calls as the sample
output run shown.
Assume the following declarative constants:
#define COL 20
#define ROW 20
Consider the following function prototype specifications:
void PopulateArray2DUnique(int A[][COL], unsigned int rowsize,
unsigned int colsize, int min, int max);
Populates the 2D Array of sizes rowsize x colsize with random integers
ranging between min and max inclusive.
void DisplayArray2D(int A[][COL], unsigned int rowsize, unsigned int
colsize);
Display the contents of a 2D array of size rowsize x colsize in a
table format; that is each line will display one row where the numbers
are separated by a single space character.
int FindLargest(int A[][COL], unsigned int rowsize, unsigned int
colsize);
Given a 2D array A of size rowsize x colsize, return the largest
integer number it contains.
int FindColSum(int A[][COL], unsigned int rowsize, unsigned int
colsize, unsigned int col_to_sum);
Calculate the sum of a given column col of a 2D array of size rowsize
x colsize. Return the sum of that column.
int Sort2DArray(int A[][COL], unsigned int rowsize, unsigned int
colsize);
Sort a 2D array of size rowsize x colsize in ascending order. i.e.
A[0][0] would have the smallest value. Example of a 3×3 sort:
1 2 3
4 5 6
7 8 9
int CopyArray2D(int A[][COL], int B[][COL], unsigned int rowsize,
unsigned int colsize);
Copy the contents of array A into array B of the same size such that
the contents of B would be exactly the contents of A. e.g. copying A
into B:
A: B:
1 2 3 1 2 3
4 5 6 –> 4 5 6
7 8 9 7 8 9
int CopyArray2DSpiral(int A[][COL], int B[][COL], unsigned int
rowsize, unsigned int colsize);
Copy the contents of array A into array B of the same size such that
the contents of B would be exactly the contents of A except they will
be in a clockwise spiral sorted order. e.g. copying A into B with
Spiral effects:
A: B:
1 2 3 1 2 3
4 5 6 –> 8 9 4
7 8 9 7 6 5
Hint: you may consider sorting A first before starting. Note that your
function should work for any size array up to ROW x COL
Specific Requirements: [25 pts]
[ 3 pts x 7] Write the complete definition and documentation for each of the 7 functions given above.
[ 1 pt] Compilation on the CS server gcc compiler without errors and warnings.
[ 3 pts] Demonstrate the complete program using a main function capable of processing the input of any
array size (not exceeding ROW and COL).
Failure to properly document your entire code will receive a mark of zero.
You are to submit the following:
– Source code file: assign2.c
– Script file demonstrating the compilation and execution : assign2.txt
To generate the script file use the following command from the CS server:
cp assign2.c assign2.bak [this step helps you backup your file in case something goes wrong]
script assign2.txt [this step creates a new file called assign2.txt]
cat assign2.c [this step will display the contents of your source code]
cc assign2.c [this step will show your compilation]
./a.out [this step will run your code so you can test it, you may need to run it a few times]
[test your code here with at least 3 different input test cases]
exit [this step is important to close the script file and complete it]
[These steps will create a file called assign2.txt. Do not edit its contents – just submit it!]
Sample OUTPUT Run
(you should repeat it at least 3 times with different input sizes such as 1×1, 3×4, 9×9, 10×5):
Testing an array of size: 3 x 4
Populate Array with unique random integers between 1 and 99…
DisplayArray2D:
41 91 12 15
81 34 33 25
45 55 94 28
FindLargest: 94
FindColSum of col 0: 167
Sort2DArray followed by DisplayArray2D:
12 15 25 28
33 34 41 45
55 81 91 94
CopyArray2D from A to B, then Display B:
12 15 25 28
33 34 41 45
55 81 91 94
CopyArray2DSpiral from A to B, then Display B:
12 15 25 28
81 91 94 33
55 45 41 34
— end run –
Hint:


