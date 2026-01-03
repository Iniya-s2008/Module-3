# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program:
```
#import library
import re

#input
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 

#keep only items that do not contain e
result = [word for word in items if not re.search(r'e', word)]

#print 
print(result)
```
Output:
<img width="741" height="191" alt="image" src="https://github.com/user-attachments/assets/fc7603cb-fc0c-417a-b3ab-6cb225ea0f07" />

## Result:
The Python program was successfully executed to filter words from a list that do not contain the letter 'e' using regular expressions.
