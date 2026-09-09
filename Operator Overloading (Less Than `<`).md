# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
~~~
class A:
    def __init__(self,a):
        self.value=value
    def __lt__(self,other):
        return self.a<other.a
ob1 = A(2)

ob2 = A(3)
if ob1<ob2:
    print("ob1 is less than ob2")
else:
    print("ob2 is less than ob1")

~~~
## Output
<img width="1001" height="323" alt="443510377-8149e2ee-f975-410a-8e0e-223a56623517" src="https://github.com/user-attachments/assets/0ceb75c8-5168-4787-82cc-a7a754bbe783" />

## Result
Therefore,The given python program is successfully verified!
