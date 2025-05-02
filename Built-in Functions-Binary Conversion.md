# Ex-2A Iterative statements

## 🎯 Aim
To write a program in python to find the sum of series 1^1+2^2+3^3... +N^N.
## 🧠 Algorithm
Read input and convert it to an integer for variable "N".
2. Define a function "sum_of_series(n)" to compute the sum of the series:
   a. Initialize the variable "total" to 0.
   b. Start a for loop from "i = 1" to "i = n" (inclusive):
      i. Compute "i ** i" (i raised to the power of "i").
      ii. Add the computed value to "total".
   c. Return the final value of "total".
3. Call the function "sum_of_series(N)" and store the result in "result".
4. Print the result in the format:
   "The sum of the series = {result}".
5. End of the program.
## 🧾 Program
```
def sum_of_series(n):

    total = 0

    for i in range(1, n + 1):

        total += i ** i  

    return total

N = int(input())

result = sum_of_series(N)

print(f"The sum of the series =  {result}") 
```
## Output
![Screenshot (66)](https://github.com/user-attachments/assets/bcb21338-37e9-44d8-b14c-8caf914fe2c1)

## Result
Thus, the required program is written and executed successfully.
