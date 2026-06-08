# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
~~~
numbers = [10, 20, 30, 40, 50]
total = sum(numbers)
print("The sum of list elements is:", total)
~~~

## Output
<img width="1559" height="988" alt="Screenshot 2025-10-20 141644" src="https://github.com/user-attachments/assets/8623318f-4881-4825-96f5-c49881f62683" />

## Result
Thus, the Python program to find the sum of all elements in a list was successfully executed

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
~~~
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1 = []

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print(l1)
~~~
## Output
<img width="1543" height="989" alt="Screenshot 2025-10-20 141743" src="https://github.com/user-attachments/assets/cb9eea4c-ea9f-4cc4-911c-065ceab09717" />

## Result
The program successfully filtered the words from the list that do not contain the letter 'e'.
