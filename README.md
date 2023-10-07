# learning-python
#hi this is subhash come join with me in this python journey.
a = int(input("Enter first number:  " ))
b = int(input("Enter SECOND number:  " ))
def calculator(a, b, operation):
    if operation == 'add':
        return a + b
    elif operation == 'subtract':
        return a - b
    elif operation == 'multiply':
        return a * b
    elif operation == 'divide':
        if b != 0:
            return a / b
        else:
            return "Division by zero is not allowed."

result = calculator(a,b, 'multiply')
print(result)
