# 🔹 What is a Variable?
A variable is a container that stores data values. It allows you to reference and manipulate data in a program.
---
```
x = 5
```
Here, x is a variable and 5 is its value.

---

# 🔹 Rules for Naming Variables:
- Can contain letters, numbers, and underscores.

- Must start with a letter or underscore (_), not a number.

- Case-sensitive (name ≠ Name).

- Avoid Python keywords (like for, if, class, etc.).

```
valid_name = 10      # valid
_name = "Hello"      # valid
2nd_place = 90       # ❌ invalid
```

---

| Rule                            | Example        | Valid? |
| ------------------------------- | -------------- | ------ |
| Starts with a letter/underscore | `age`, `_name` | ✅      |
| Cannot start with a number      | `2value`       | ❌      |
| No special characters           | `name@`        | ❌      |
| Cannot use keywords             | `if`, `for`    | ❌      |
| Case-sensitive                  | `Name`, `name` | ✅      |

--- 
# 🔹 Types of Variables (Dynamic Typing)
### Python automatically detects the type based on the value assigned.
```
a = 10             # int
b = 3.14           # float
c = "Hello"        # string
d = True           # boolean

```

## Use type() to check the type:
```
print(type(a))     # <class 'int'>
print(type(c))     # <class 'str'>
```
---
# 🔹 Variable Reassignment
## You can change a variable's value or type anytime.

```
x = 10
x = "Now I'm a string"
```

---


