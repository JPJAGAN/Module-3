## Strings-Remove Nth Index Character from a String
## Aim
To write a Python program that accepts a string and removes the character at a specified index.

## Algorithm

Define a function named remove that takes the input string as an argument.
Read the index n from the user input.
Initialize an empty string a to store the new string.
Iterate over each index of the string using a for loop.
Check if the current index i is not equal to n.
If i != n, append the character at index i to string a.
After the loop, return the modified string a.
Print the final result.
## Program
```
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
```
## Output
<img width="884" height="254" alt="{24BAF028-52B9-41A5-B97E-4D285564BA74}" src="https://github.com/user-attachments/assets/bc254635-6a99-479f-8fd4-c8d3b9460323" />


## Result
Thus the program executed successfully.
