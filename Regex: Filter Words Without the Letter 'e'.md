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
