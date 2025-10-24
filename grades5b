#Name: B**** L*****
#Due Date: 10/16/25
#Description: A Class of n students
#took a quiz.  The integer grades (0-100)
#are available to you.  Determine the
#class average using a while loop.
#Only programming techniques that have been
#discussed in class may be used.
#change grades5 so that it "error proofs" the inputs
#acceptable number of students is between 1 and 25
#acceptable grades are 0-100
#also as the grades are input it should tell what grade is being input.
#Enter grade 1:
#Enter grade 2:
#...

##set sum to zero
summ = 0

##set grade counter to one
gradeCounter = 1

##set totalStudents to the input value of the total number of students
totalStudents = int(input("How many students are in class? "))
print()
while totalStudents < 1 or totalStudents > 25: #check for valid number of students (can't have no students and legally only 25 per class)
    print("That is an unacceptable amount of students, enter 1-25. ")
    print()
    totalStudents = int(input("How many students are in class? "))
    print()

##While grade counters is less than or equal to totalStudents
while gradeCounter <= totalStudents:

    grade = float(input("Enter grade " + str(gradeCounter) + ": ")) #prompt user to enter the nth grade
    while grade < 0 or grade > 100: #check if grade is valid
        print()
        print("That is an unacceptable grade, enter 1-100. ")
        print()
        grade = float(input("Enter grade " + str(gradeCounter) + ": "))  # prompt user to enter the nth grade
    summ = summ + grade #add the grade into the total
    gradeCounter = gradeCounter + 1 #add one to the grade counter

##set the class average to the total divided by max
classAverage = summ / totalStudents

##print class average
print()
print("The class average is: " + str(classAverage))
