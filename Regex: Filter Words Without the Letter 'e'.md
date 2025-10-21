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

## 🧾 Program
```
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']   #'They ate 5 apples and 5 oranges'
result=[]
for i in items:
    if not  re.search('e',i):
          result.append(i)
print(result)
```
## Output
<img width="589" height="354" alt="m3-2" src="https://github.com/user-attachments/assets/a4913ddb-0854-4230-9d7f-483f22f70465" />

## Result
successfully created
