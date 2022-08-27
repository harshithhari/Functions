# Functions
Functions Examples 
****'''Write a Python function to sum all the numbers in a list. Go to the editor****
Sample List : (8, 2, 3, 0, 7)'''

"""def sum(numbers):
    total = 0
    for x in numbers:
        total += x
    return total
print(sum((8, 2, 3, 0, 7)))"""

****''' Write a Python function to multiply all the numbers in a list. Go to the editor****
Sample List : (8, 2, 3, -1, 7)'''

def mul(n):
    y=1
    for i in n:
        y=y*i
    return y
print(mul((8, 2, 3, -1, 7)))
