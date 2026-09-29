# Day-112-Search-Element
# Python Day 112 - Search an Element

This program checks whether a particular element is present in a list using the `in` operator.

## Example

List:

```text
[10, 20, 30, 40, 50]
```

Element to search:

```text
30
```

Output:

```text
30 is present in the list.
```

## Concepts Used

* List
* `in` operator
* `if-else`
* Boolean condition
* Variables

## How It Works

1. A list of numbers is created.
2. The number to search is stored in a variable.
3. The `in` operator checks whether the number exists in the list.
4. If the number is present, the `if` block runs.
5. Otherwise, the `else` block runs.

## Python Code

```python
numbers = [10, 20, 30, 40, 50]

print("List:", numbers)

number = 30

if number in numbers:
    print(number, "is present in the list.")
else:
    print(number, "is not present in the list.")
```

## Output

```text
List: [10, 20, 30, 40, 50]
30 is present in the list.
```

## Goal

The goal of this project is to understand the `in` operator and learn how to search for an element in a Python list.
