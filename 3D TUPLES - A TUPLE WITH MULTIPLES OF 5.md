# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
l=[]
n=int(input())
for i in range(5,n,5):
    l.append(i)
t=tuple(l)
print(t)
```

### OUTPUT
<img width="781" height="239" alt="{49F404D2-A54B-4F41-BAE7-0BCCF4D3F59D}" src="https://github.com/user-attachments/assets/ef934713-74d9-4d1e-b3b6-214d02ed9225" />

### RESULT
Thus a Python program to create a tuple containing all multiples of 5 up to a given number N was executed and implemented successfully.
