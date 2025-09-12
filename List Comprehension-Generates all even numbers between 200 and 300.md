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
class Generate:

    def __init__(self, first,d,last):
        self.first = first
        self.d = d
        self.last=last
    def Ap_generate(self):
        L=[i for i in range(self.first,self.last+1,self.d)]
        return L


Series = Generate(200,2,301)

print(Series.Ap_generate())



## OUTPUT:
<img width="1130" height="224" alt="Screenshot 2025-09-12 142554" src="https://github.com/user-attachments/assets/47f59474-b116-42e2-ab52-9931d539929c" />

<img width="1185" height="238" alt="Screenshot 2025-09-12 142616" src="https://github.com/user-attachments/assets/014871ec-e28d-45bc-a805-a28bdcc09d77" />

## RESULT:
Thus, a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list is verified.
