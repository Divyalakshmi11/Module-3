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

# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
~~~
def remove(string, n):
    a = ""
    for i in range(len(string)):
        if i != n:
            a += string[i]
    return a

string = input("Enter a string: ")
n = int(input("Enter the index to remove: "))
result = remove(string, n)
print("Modified string:", result)
~~~
## Output
<img width="1554" height="981" alt="Screenshot 2025-10-20 142004" src="https://github.com/user-attachments/assets/c61e6c3e-e15b-477a-99fb-cd00a3e4217f" />

## Result
The program successfully removed the character at the specified index from the string.




## Result
The program successfully removed the character at the specified index from the string.
