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



# 🔹 Multiple Assignment
## Assign values to multiple variables at once:

```
a, b, c = 1, 2, 3
x = y = z = 100  # All assigned 100
``` 



---


# 🔹 Swapping Values
## Python lets you swap variable values easily.

```
a = 5
b = 10
a, b = b, a
print(a, b)  # 10 5
```
---

# 🔹 Constants (By Convention)
## Python doesn't have true constants, but you can use uppercase names:

```
PI = 3.14159
MAX_USERS = 100
```

---
# 🔹 Variable Naming Styles


| Style       | Example     | Use Case                |
| ----------- | ----------- | ----------------------- |
| snake\_case | `user_name` | ✅ Recommended in Python |
| camelCase   | `userName`  | ❌ JavaScript style      |
| UPPER\_CASE | `MAX_SPEED` | ✅ For constants         |


---


# 🔹 String Variables
```
first_name = "Thanusan"
greeting = "Hello, " + first_name
print(greeting)  # Hello, Thanusan
```
---

# 🔹 Numeric Variables
```
price = 49.99
quantity = 3
total = price * quantity
print("Total:", total)
```

---





# 🔹 Boolean Variables
```
is_online = True
is_empty = False
print(is_online)  # True
```


---


# 🔹 type() and isinstance()
```

x = 42
print(type(x))                # <class 'int'>
print(isinstance(x, int))     # True
```

# 🔹 Reserved Keywords (Cannot be used as variable names)
``` Examples: and, as, break, class, continue, def, else, False, for, if, import, None, True, while, etc.```



---

# ✅  Practice Task
## Try creating the following variables:
```

your_name = "Your Name"
age = 20
height = 5.7
is_student = True
```

## Then print them all using:
```
print(your_name, age, height, is_student)
```






























