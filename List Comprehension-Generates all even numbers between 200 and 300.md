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
Add Code Here
```
  first=int(input())
  difference=int(input())
  last=int(input())
  
  print("First Number",first)
  print("Difference",difference)
  print("Last Number",last)
  
  ap_series=[i for i in range(first,last+1,difference)]
  print(ap_series)
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/94f28055-d12e-42b5-8057-bcc9be83a974)

## RESULT:
Thus, the program has been execueted successfully.
