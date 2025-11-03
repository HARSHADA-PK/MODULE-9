# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:
```
m,n=input().split()
l=[]
for i in range(int(m)):
    row=[]
    for j in range(int(n)):
        value=int(input())
        row.append(value)
    l.append(row)
transpose=[[Row[i] for Row in l] for i in range(len(l[0]))]
print(l)
print(transpose)
```

## OUTPUT:
<img width="1042" height="588" alt="image" src="https://github.com/user-attachments/assets/02a55922-1d19-40c6-aafb-94a6c5a98729" />



## RESULT:
Thus, the program has been execueted successfully.


