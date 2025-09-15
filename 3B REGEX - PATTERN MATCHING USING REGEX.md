# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
import re
str=input()
x=re.search("bb",str)
if x:
    print("Found a match!")
else:
    print("Not matched!")

```
### OUTPUT
<img width="612" height="223" alt="{B9041947-986A-4FA9-B6F8-F65A9E847C77}" src="https://github.com/user-attachments/assets/1175a122-c0e2-4729-ba25-dbe2cd7578a2" />

### RESULT
Thus a Python program that matches a string containing an 'a' followed by two to three 'b' characters using regular expressions was executed and implemented successfully.
