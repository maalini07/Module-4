# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
msg=[5, 10, 20]
try:
    print(msg[5])
except IndexError:
    print("You're out of list range")
```

## Output
<img width="601" height="160" alt="447319988-9be66b38-0948-4868-b629-4f4b25957abd" src="https://github.com/user-attachments/assets/e2d63649-487c-4695-8de1-38a623d6cbf1" />


## Result
Thus, the program as executed successfully.
