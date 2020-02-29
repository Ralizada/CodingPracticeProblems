"""
**Google Coding Interview Question**

Write a recursive function that returns the sum of the digits of a given integer

Input: 12345

Output: 15
"""

def sum_digits(n):
    if n < 10:
        return n
    else:
        return n % 10 + sum_digits(n // 10)

print(sum_digits(int(input("Enter an integer: "))))
