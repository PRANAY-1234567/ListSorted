✅ Check if a List is Sorted in Python
📌 Description

This program checks whether a given list of numbers is already sorted in ascending order.
It compares the original list with a sorted version of itself.

🧩 Problem Statement

Given a list:

[1, 2, 3, 4]


Determine whether the list is sorted or not.

✅ Code
numbers = [1, 2, 3, 4]

if numbers == sorted(numbers):
    print("List is sorted")
else:
    print("List is not sorted")

🧠 Explanation

sorted(numbers) returns a new list sorted in ascending order

The program compares the original list with the sorted list

If both are the same → the list is sorted

Otherwise → the list is not sorted

🛠 Concepts Used

Lists

sorted() function

Conditional statements

🎯 Example Output
List is sorted

🚀 Use Cases

Interview preparation

Data validation

Beginner Python practice

Checking data before processing

🔧 Possible Improvements

Check for descending order

Avoid using sorted() (manual logic)

Convert into a function

Add user input support

👨‍💻 Author

Pranay Jadhao
