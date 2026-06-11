## List Operations in Python: Sum of List Items
## Aim
To write a Python program that calculates the sum of all elements in a list.

## Algorithm

Define a list of numbers.
Use Python’s built-in sum() function to calculate the total.
Print the result.
## Program
```
items=[153,147,124,102]
print(sum(items))
```

### Output
<img width="684" height="196" alt="{A9FB8EA4-DE86-41FC-9DF3-C3037FB3D009}" src="https://github.com/user-attachments/assets/28440671-a083-442a-92bc-92c568745c0e" />

## Result
Thus the program executed successfully.

## Regex in Python: Filter Words Without the Letter 'e'
## Aim
To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

## Algorithm
Import the re module.
Initialize an empty list l1 to store results.
Define a list of words:
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
Iterate through each word in the list:
Use re.search(r"e", i) to check if the word contains 'e'.
If not, append the word to l1.
Print the final filtered list.
## Program
```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
```
## Output
<img width="657" height="197" alt="{4D2C24B5-C0A6-4782-AD5B-81A063DEEE76}" src="https://github.com/user-attachments/assets/f0b5ba83-7df7-4464-84eb-b81ad2b2c91d" />


## Result
Thus the program executed successfully.

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

## Strings-Palindrome Check in Python (Without Built-in Functions)
## Aim
To write a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions.

## Algorithm
Assign the string "google" to a variable.
Reverse the string manually using slicing ([::-1]).
Compare the original string with the reversed string.
If they are equal, print that the string is a palindrome.
Otherwise, print that it is not a palindrome.
Execute the program.
## Program
```
a=input()
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```
## Output

<img width="1046" height="171" alt="{3ABC3C39-4F64-4269-B2FD-40C1E5F8ABFC}" src="https://github.com/user-attachments/assets/c3c1d4bf-5807-4dcc-b7fb-c7eddae07cc0" />

## Result
Thus the program executed successfully.

## Tuple in Python: Check Element Existence
## Aim
To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.

## Algorithm
Define a tuple x with some letters and numbers.
Use the in operator to check if the string 'n' exists within the tuple.
Use the in operator to check if the integer 8 exists within the tuple.
Print the results.
## Program
```
tuplex = input()
print("n" in tuplex)
print("8" in tuplex)
print("Words without 'e':", l1)
```
## Output
<img width="1047" height="304" alt="{C9E9B24D-7EEC-4657-9CFA-5263CFA4C080}" src="https://github.com/user-attachments/assets/4aa4d9e1-ab56-40bf-9e0c-e8f9bc456f6f" />

## Result
Thus the program executed successfully.
