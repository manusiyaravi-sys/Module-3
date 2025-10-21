# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
num=int(input())
rev=0
temp=num
while temp>0:
   d=temp%10
   rev=rev*10+d
   temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
```


## Output
<img width="1193" height="490" alt="m2-5" src="https://github.com/user-attachments/assets/427ed052-81a2-45fa-b64a-0035691222d5" />

## Result
successfuly created
