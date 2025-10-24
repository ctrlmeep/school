total = float(input("How much would you like to invest? "))
while total <= 0:
    print("\nInvestment must be greater than 0.\n")
    total = float(input("How much would you like to invest? "))

interest = float(input("What is the annual interest rate? "))
while interest <= 0 or interest >= 25:
    print("\nInvestment rate must be greater than 0 and less than 25%. \n")
    interest = float(input("What is the annual interest rate? "))
interest = interest / 100 + 1

time = int(input("How long would you like to invest it? "))
while time <= 0:
    print("\nTime for investment must be greater than 0. \n")
    time = int(input("How long would you like to invest? "))

print("\nYear       Amount on Deposit")
for i in range(time + 1):
    print(str(i) + " " * (12 - len(str(i))) + f"${total:.2f}")
    total = total * interest
