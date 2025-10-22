#simple 4 function calculator (additionally with exponentiation, root, and modulus)
#with checks for dividing by zero and for improper inputs
def get_valid_number(prompt):
    while True:
        try:
            return float(input(prompt))
        except ValueError:
            print("Please enter a valid number!")
            print()

def get_operation():
    print("What operation would you like to perform?")
    print("+ : Addition")
    print("- : Subtraction")
    print("* : Multiplication")
    print("/ : Division")
    print("^ : Exponentiation")
    print("r : Root")
    print("% : Modulus")
    print("! : Factorial")
    operation = input("Enter the operation symbol (+, -, *, /, ^, r, %, !): ")
    #if operation == "!":

    return operation

def compute():
    while True:
        first_number = get_valid_number("What is the first number? ")
        print()
        operation = get_operation()
        print()
        if operation == "!":
            num = int(first_number)
            if num < 0:
                print("Factorial is not defined for negative numbers.")
                print()
                continue  # Go back to start of loop
            elif num == 0:
                result = 1
            else:
                factorial_result = 1
                for i in range(1, num + 1):
                    factorial_result *= i
                result = factorial_result
            print(f"Answer: {result}")
            break
        second_number = get_valid_number("What is the second number? ")
        print()

        if operation == "+":
            result = first_number + second_number
            print(f"Answer: {result}")
            break
        elif operation == "-":
            result = first_number - second_number
            print(f"Answer: {result}")
            break
        elif operation == "*":
            result = first_number * second_number
            print(f"Answer: {result}")
            break
        elif operation == "/":
            if second_number == 0:
                print("Error: Cannot divide by zero!")
                print()
            else:
                result = first_number / second_number
                print(f"Answer: {result}")
                break
        elif operation == "^":
            result = first_number ** second_number
            print(f"Answer: {result}")
            break
        elif operation == "r":
            if second_number <= 0:
                print("Error: Cannot divide by zero!")
            else:
                result = first_number ** (1 / second_number)
                print(f"Answer: {result}")
                break
        elif operation == "%":
            if second_number == 0:
                print("Error: Cannot divide by zero!")
                print()
            else:
                result = first_number % second_number
                print(f"Answer: {result}")
                break
        else:
            print("Invalid operation! Please use +, -, *, or /.")
            print()

def main():
    print("Calculator")
    print("----------")
    print()
    while True:
        compute()
        print()
        if input("Press ENTER to continue or type 'quit' to exit: ").lower() == "quit":
            break
        print()

if __name__ == "__main__":
    main()
