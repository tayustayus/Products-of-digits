# Products-of-digits
# write a program to calculate the product of digits
def product(x, y):
    a_product = x * y
    return a_product

user_value1 = float(input("Enter number1: "))
user_value2 = float(input("Enter number2: "))        
Enter number1: 56
Enter number2: 42
print(product(user_value1, user_value2))
2352.0

# for a string of numbers this will also suffice
import numpy as np
n = int(input("Enter the digits:  "))
print(np.product([int(i) for i in str(n)])
