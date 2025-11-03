# 🧮 SORTING ALGORITHMS: Insertion Sort Using a Class

This program demonstrates how to implement the **Insertion Sort algorithm** using a Python class. It allows the user to input a list of numbers, sorts them using the insertion sort technique, and displays the sorted list.

---

## 🎯 Aim

To develop a Python class with functions to:
- Create a list of integers
- Sort it using the **Insertion Sort** algorithm
- Display the sorted list

---

## 🧠 Algorithm

1. **Start the program**
2. **Define a class** `InsertionSorter`
3. Inside the class:
   - `create_list()`:
     - Read number of elements
     - Store them in a list
   - `insertion_sort()`:
     - Iterate from the second element to the end
     - Move elements greater than the key to one position ahead
     - Insert the key at the correct position
   - `print_list()`:
     - Print the sorted list
4. **Create an object** of the class
5. **Call** the methods in order: `create_list()`, `insertion_sort()`, and `print_list()`
6. **End the program**

---

## 💻 PROGRAM:
```
def create_list():
    n=int(input())
    l=[]
    for i in range(n):
        value=int(input())
        l.append(value)
    return l
def insertion_sort(l):
    for i in range(1,len(l)):
        key=l[i]
        j=i-1
        while(j>=0 and key<l[j]):
            l[j+1]=l[j]
            j-=1
        l[j+1]=key
    return l
def print_list(l):
    for el in l:
        print(el)
L1=create_list()
print("Before Sorting")
print_list(L1)
print("After Sorting")
print_list(insertion_sort(L1))
```

## OUTPUT:
<img width="930" height="674" alt="image" src="https://github.com/user-attachments/assets/462e0abc-e780-4db3-8536-14a6a6d43900" />


## RESULT:
Thus, the program has been execueted successfully.
