# Ex-2D LOOPING
##  Aim
To print a right-angled triangle pattern of numbers, where each row contains numbers in increasing order starting from 1.
## Algorithm
. Read the number of rows from the user and store it in the variable "num_rows".

2. Start an outer for loop to iterate from 1 to "num_rows" (inclusive):
   a. Let the current iteration variable be "i".
   b. For each "i", start an inner for loop to iterate from 1 to "i" (inclusive):
      i. Let the inner iteration variable be "j".
      ii. Print the value of "j", followed by a space, without moving to a new line.
   c. After completing the inner loop, move to the next line by using "print()".

3. End of the program.
## Program
```
num_rows = int(input())

for i in range(1, num_rows + 1):

    for j in range(1, i + 1):

        print(j, end=' ')

    print()   
```
## Output
![Screenshot (69)](https://github.com/user-attachments/assets/1582dae6-6094-455b-a8fb-9dacd71d8560)
## Result
Thus, the required program is written and executed successfully.
 
