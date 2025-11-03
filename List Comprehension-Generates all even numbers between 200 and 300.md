# 🧾 List Comprehension:Generates all even numbers between 200 and 300
## 🎯 AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**

---

## 💻 PROGRAM:
```
class Generate:
    def __init__(self,first,d,last):
        self.first=first
        self.d=d
        self.last=last
    def Ap(self):
        L=[i for i in range(self.first,self.last+1,self.d)]
        return L
a=int(input())
b=int(input())
c=int(input())
Series=Generate(a,b,c)
print(Series.Ap())
```

## OUTPUT:
<img width="1044" height="217" alt="image" src="https://github.com/user-attachments/assets/ddc2466a-5310-4966-aa7b-e1d2ed4b682d" />


## RESULT:
Hence Generated even numbers between 200 and 300 using list comprehension in a class
