# python-assignment-1

# Basic calculator program

def calculator():
    first_digits = 15
    second_digits = 10
    
    operation = input("+, - ,*, /")

    if operation == '+':
        print('{first_digits} + {second_digits}')

    elif operation == '-':
        print('{first_digits} - {second_digits}')

    elif operation == '*':
        print('{first_digits} * {second_digits}')

    elif operation == '/':
        if second_digits != 0:
           print('{first_digits} / {second_digits}')
        else:
            print("ERROR")
             
