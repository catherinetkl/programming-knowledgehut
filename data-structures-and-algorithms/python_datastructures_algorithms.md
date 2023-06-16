# Python

## Big O

### Time complexity
a function that measures how long an algorithm takes in terms of the quantity of input it receives\
Measured in the number of operations that it takes to complete something

### Space complexity
a function that measures how much memory (space) an algorithm requires to the quantity of input to the method\
if preserving space is the main priority and time taken for the operations to complete is not held with as much importance

### 3 Letters for Time & Space complexity
Ω (omega), θ (theta) and O (omicron)
example: a list of 7 integers, need to build a for loop to iterate through list to find specific number

best case scenario (denoted by Ω): 
> if target integer: 1
  - find 1 in one operation
average case scenario (denoted by θ):
> if target integer: 4
  - iterate through four integers to get to 4
worst case scenario (denoted by O): 
> if target integer: 7
  - iterate through the entire list to get to 7

### O(n)
1. Create a function named, print items
2. Pass it a number, n 
3. Have a <b>for loop</b> that runs for n times
4. Print <b>i</b> from <b>for loop</b>