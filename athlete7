#Name: B**** L*****
#Due Date: 10/23/25
#Program Description: Create a python application that will calculate an athlete’s target heart rate.  
#The formula for calculating the THR = 50-85% of Max Heart Rate.  MHR = 220 – age(in years).
#Input should be First Name and the year you were born.
#Output should be Minimum and Maximum Target Heart Rate and age.
#Error proof your code.  Minimum age 13, Max age: (you should be able to determine from the formula)

name = input("What is your name? ")

birthYear = int(input("In what year were you born? ")) #age input and validation
age = 2025 - birthYear
while age < 13 or age > 219:
    print("\nError, you must be 13 to *** years old to use the program.\n")
    birthYear = int(input("In what year were you born? "))
    age = 2025 - birthYear

maxHr = 220 - age

print("\nHello, " + name + ".")
print("Your age is " + str(age) + ".")
print("Your Target Heart Rate is " + str(round(maxHr * 0.5)) + " to " + str(round(maxHr * 0.85)) + ".")
