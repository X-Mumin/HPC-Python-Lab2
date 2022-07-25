# HPC-Python-Lab2
to build a simple School Management System using Python
write a program to build a simple School Management System using Python which can perform following operations:

base class: for all people, name, id, phone, email, location
child class: students with extra attribute: tuition fees, grade, year
child class: Teacher, with attribute: Subjects to teach, salary

make sure you can create students and teachers objects (class instance)

we need to add the ability to add subjects  and grades to students, modify them,  calculate total percentage for all subjects passed by student and check if the student has passed or failed ( A=90 or more, B: 80 or more, C: 70 or more, D: 60 or more, otherwise s/he gets F for failing the subject)

we need to be able to search all students or teachers using their id



hint:.

class A:
      instances = [ ]
      def __init__(self):  #in the constructor
                self.__class__.instances.append(self)


then I need a way to be able to get the input interactively from the user when you run the script to add a person, you need to specify the type of the person first then add the details as per the instructions above for each class

and if you enter a wrong data type then it will give you exception error of the type of data expected
