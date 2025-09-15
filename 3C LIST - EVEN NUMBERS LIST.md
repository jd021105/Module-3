# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

---

### PROGRAM

```
def createlist(n):
    l=[]
    for i in range(2,n):
        if i%2==0:
            l.append(i)
    print(l)
```

### OUTPUT
<img width="696" height="217" alt="{49237BBC-E635-49C1-8588-451DC130D7FF}" src="https://github.com/user-attachments/assets/87577a06-9221-48fc-a273-f088d20f5148" />

### RESULT
Thus a Python function that accepts a number N and creates a list containing all even numbers up to N was executed and implemented successfully.
