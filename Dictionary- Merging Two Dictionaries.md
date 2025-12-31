## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
dict1 = {
    "name": "Alice",
    "age": 25,
    "city": "New York"
}

dict2 = {
    "age": 30,
    "country": "USA"
}

def merge(d1, d2):
    merged_dict = {**d1, **d2}  
    return merged_dict


result = merge(dict1, dict2)
print(result)
```

## Output
<img width="813" height="112" alt="528595770-c7bc86eb-98a5-4efa-8670-404a7b255f52" src="https://github.com/user-attachments/assets/e4ad8191-1502-4b9a-8c96-a7c53aecf402" />

## Result
Thus a Python program that merges two dictionaries and combines their key-value pairs is executed successfully.
