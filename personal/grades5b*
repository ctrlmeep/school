summ = 0
while True:
    classSize = int(input("How many students are in class? "))
    if 1 <= classSize <= 25:
        break
    else:
        print("\nThat is an unacceptable amount of students, enter 1-25. \n")
print()

for i in range(classSize):
    while True:
        grade = float(input("Enter grade " + str(i + 1) + ": "))
        if 0 <= grade <= 100:
            break
        else:
            print("\nThat is an unacceptable grade, enter 0-100. \n")
    summ += grade

print("The class average is: " + str(summ / classSize))
