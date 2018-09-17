# pythonclass Plant():
    def __init__(self,plant_type):
        self.__plant_type=plant_type
    def message(self):
        print("I'm a plant")
class Flower(Plant):
    def __init__(self):
        Plant.__init__(self,'tree')
    def message(self):
        print("I'm a flower")
class Tree(Plant):
    def __init__(self):
        Plant.__init__(self,'tree')
    def message(self):
        print("I'm a tree")

a= Plant('sapling')
b= Tree()
c= Flower()
d= Plant('cactus')
a.message()
b.message()
c.message()
d.message()

class Car:
    def __init__(self,model,make,speed):
        self.__year_model=model
        self.__make=make
        self.__speed=speed
    def accelerate(self):
        self.__speed += 5
    def brake(self) :
        if self.__speed >= 5:
            self.__speed -= 5
        else:
            print ("The car has stopped.")
    def get_speed (self):
        return self.__speed
def main():
    model=input("Please the car's year:")
    make=input("Please the car's make:")
    speed=int(input("Please the car's current speed in mph:"))
    car1=Car(model,make,speed)
    car1.accelerate()
    newspeed=car1.get_speed()
    print("Now the", str(model),str(make),"is going", str(newspeed),"mph.")
main()

    
    


        
    

        

print("Welcome to the automobile monthly payment calculator")
def main():
    initial=int(input("Enter the initial cost of the automobile:"))
    down=int(input("Enter the down payment:"))
    irate=float(input("Enter the interest rate:"))
    payment1=monthlypayment(initial,down,irate,12)
    payment2=monthlypayment(initial,down,irate,24)
    payment3=monthlypayment(initial,down,irate,36)

def monthlypayment(initial,down,irate,months):
    payment=((initial-down)*(irate/12)*(1+irate/12)**months)/((1+irate/12)**monthlypayment)
    return payment
main()

    
                                                              
                                                              
                                                              

prizes={'door1':100,'door2':200,'door3':1000}
for i in prizes:
    print('Behind', i,'is $' + str(prizes[i]))
    print("Welcome to the room calculator. This will tell you the area of each room in your house as well as the total area of the house in square feet")
rooms=int(input("How many rooms are iclass Pet:
    def __init__(self,name,age,phone_number):
        self._name=name
        self._age=age
        self.phone_number=phone_number

       def set_name(self,name):
           self.__name=name

       def set_age(self,age):
           self.__age=age

        def set__phone_number(self,phone_number):
            self.__phone_number=phone_number

        def get_name(self):
            return self.__name
        def get__age(self):
            return self.__age
        def get__phone_number(self):
            return self.__phone_number
class Cat(Pet):
    def __init__(self,name,age,phone_number):
        Pet.__init__(self,name,age,phone_number)
    
    def main():
        name=""
        age=""
        phone number=""
        cust_number= 0
     

        name=input("Enter the name:")
        age=input("Enter the age:")
        phone_number=input("Enter the phone number:")
        
      

                customer=person.Customer(name,age,phone_number)

                print('Customer info:')
                print('Name:', cust.get_name())
                print('Age:', cust.get_age())
               

                
class Dog(Pet):
    def __init__(self,name,age,phone_number):
        Pet.__init__(self,name,age,phone_number

    def main():
        name=""
        age=""
        phone number=""
      
     

        name=input("Enter the name:")
        age=input("Enter the age:")
        phone_number=input("Enter the phone number:")
 
                customer=person.Customer(name,age,phone_number)
def main():
    num1=int(input('Enter an integer:'list1=[89,11,45,34]
def get_max(maximum,list2,start,end):mon=int(input('Enter the sales for Monday:'))
tues=int(input('Enter the sales for Tuesday:'))
wed=int(input('Enter the sales for Wednesday:'))
thu=int(input('Enter the sales for Thursday:'))
fri=int(input('Enter the sales for Friday:'))
list1 = ['Monday','Tuesday','Wednesday','Thursday','Friday']
sales= [mon,tues,wed,thu,fri]
i=0
total=sum(sales)
for num in list1:
    print(num,"sales is", sales[i])
    i+=1
print("The total sales of the week is "+ str(total))
    

list1=['Amy','Molly','Barry','Hal','Nate']
grades=[89, 90, 78, 82, 95]
avg=sum(grades)/float(len(grades))
i=0
for num in list1:
	print(num, "got a score of", grades[i])
	i+=1
print("The average score is", avg)
list1.append('Mary')
grades.append(85)
i = 0
num =0
avg=sum(grades)/float(len(grades))
for num in list1:
	print(num, "got a score of", grades[i])
	i+=1list1=['Amy','Molly','Barry','Hal','Nate']
grades=[89, 90, 78, 82, 95]
list2=list(list1)
list2.sort()
print('Alphabetically sorted:')
for num in list2:
	i=list2.index(num)
	print(num,'got a score of',grades[i])
grades2=list(grades)
grades2.sort()
print('Sorted by grade:')
for num in grades2:
	i=grades.index(num)	
	print(list1[i], 'got a score of', num)


print("Welcome to the die generator. This program will roll two pair of die and display the value of each die and the sum")
import random
answer=input("Enter any key to roll the pair of die or 0 to quit")
while answer!="0":
	a=random.randint(1,6)
	print("The first dice is:",a)
	b=random.randint(1,6)
	print("The second dice is",b)
	print("The sum is:",a+b)
	answer=input("Enter any key to roll the pair of die or 0 to quit")
print("Thanks!")	
file=open("lab8bdoc.txt",'w')
print("Welcome to the address book creator!")
variable=input("Do you wish to continue to enter something into the address book (Enter y for yes)")
while variable=='y':
	name=input("Please enter your first name:")
	last=input("Please enter your last name:")
	email=input("Please enter your email:")
	phone=input("Please enter your phone number:")
	file.write(name+" "+last+" "+email+" "+phone+"\n")
	input("Do you wish to continue to enter something into the address book? (Enter y for yes)")
print("Thank you for using the address book creator")
file=open("lab8doc.txt",'w')
for count in range(1,5):
    file.write("Hello\n")
file.close()username=input('Please enter a username')
email=input('Please enter your email address')
password=input('Please enter a password')
print('Thank you for creating an account')
password1=input('Welcome back'+ username+ '! Please enter your password:')
print("Welcome to the automobile montnum1=2
num2=int(input('Type in an integer number:'))
ifnum1>num2
print('My number is", num1, "which is greater than',num2)
else:name=input('Please enter your name:')
phone=input('Please enter your phone number:')
address=input('Please enter your address:')
print('Thank you the following has been added to the address book:')
print('name', name)
print('phone', phone)
print('address', address)

print('My number is", num1, "which is less than', num2)	hly payment calculator")
def main():
	initial=float(input("Enter the initial cost of the automobile:"))
	down=float(input("Enter the down payment:"))
	irate=float(input("Enter the interest rate:"))
	payment1=monthlypayment(initial,down,irate,12)
	payment2=monthlypayment(initial,down,irate,24)
	payment3=monthlypayment(initial,down,irate,36)
	print("The monthly payment for 12 months is:",payment1)
	print("The monthly payment for 24 months is:",payment2)
	print("The monthly payment for 36 months is:",payment3)




def monthlypayment(initial,down,irate,months):
	payment=((initial-down)*(irate/12)*(1+irate/12)**months)/((1+irate/12)**months-1)
	return payment
main()	 



if password==password1:
	print("Your password is correct")
else:
	print('Incorrect password!')	
file=open("lab8doc.txt",'r')
for line in file:
    print(line+"\n")studentTotal = 0
classTotal=0
NumStudents=int(input(“Enter the number of students: “))
NumTests=int(input(“Please enter the number of test taken: “))
for StuNum in range(1,NumStudents+1):
	print(“Please enter information fdef square(x):
    returnx**2
def main():
    a=int(input("Please enter a number:"))
    b=square(a)
    print("The square of the number you entered is",b)
    main()
or student “+str(StuNum))
	for TestNum in range(1, NumTests+1):
		grade=float(input(“Enter test “+str(TestNum)+ “: ”) )
		studentTotal = studentTotal + grade
	average = studentTotal/NumTests
	print( “The average for student “+str(StuNum)+ “  “+str(average))
	classTotal=classTotal+average
	studentTotal=0
average = classTotal/NumStudents
print(“The average is “+ str(average))

file.close()
          

Python 3.5.2 (v3.5.2:4def2a2901a5, Jun 26 2016, 10:47:25) 
[GCC 4.2.1 (Apple Inc. build 5666) (dot 3)] on darwin
Type "copyright", "credits" or "license()" for more information.
>>> WARNING: The version of Tcl/Tk (8.5.9) in use may be unstable.
Visit http://www.python.org/download/mac/tcltk/ for current information.
answer=input("Would you like to continue? (Enter 'y' for yes or 'n' for no): ")
Would you like to continue? (Enter 'y' for yes or 'n' for no): y
>>> while answer.strip()!='y' and answer.strip()!='n':
	answer=input("Incorrect input. Please enter 'y' for yes or 'n' for no")
>>> while answer.strip()=='y':
	Grade1=input("Enter the grade of the first test.")
	Grade2=input("Enter the grade of the second test.")
	Grade3=input("Enter the grade of the third test.")
	Average=(Grade1+Grade2+Grade3)/3
	print("The average of these test scores is",Average)
	answer=input("Would you like to continue? (Enter \'y\' for yes or \'n\' for no):")
	while answer.strip()!='y' and answer.strip()!='n':
		answer=input("Incorrect input. Please enter \'y\' for yes or \'n\' for no")
		

print("The new average score is", avg)

rooms=input("How many rooms are in your house?")
rname1=input("What is the name of room 1?")
rwidth=float(input("What is the width of room 1 in feet?"))
rlength=float(input("What is the length of room 1 in feet?"))
rname2=input("What is the name of room 2?")
rwidth2=float(input("What is the width of room 2 in feet?"))
rlenght2=float(input("What is the length of room 2 in feet?"))
rname3=input("What is the name of room 3?")
rwidth3=float(input("What is the width of room 3 in feet?"))
rlength3=float(input("What is the length of room 3 in feet?"))
print("Room Area")
print("Room 1:", rname1, rwidth, "*", rlength, "==", rwidth * rlength)
print("Room 2:", rname2,)
print("Room 3:", rname3,)	

import random
random.randint(1,10)
a=random.randint(1,10)
print("The selected random number is",a)
b=random.choice('abcde')
print("The selected letter number is",b)

    if start>end:
        return maximum
    elif list2[start]>maximum:
        return get_max(list2[start],list2,start+1,end)
    else:
        return get_max(maximum,list2,start+1,end)

def get_sum(list2,start,end):
    if start>end:
        return 0
    else:
        return list2[start]+get_sum(list2,start+1,end)

def main():
    maxi=get_max(list1[0],list1,list1[1],len(list1)-1)
    print(maxi)
    summi=get_sum(list1,0,len(list1)-1)
    print(summi)
main()    
        
        
    

))
    num2=int(input('Enter another integer:'))
    product= multiply(num1,num2)
    print(str(num1), 'times', str(num2), 'is', product)
def multiply(num1,num2):
    if num2==0:
        return 0
    elif num2<0:
        return multiply(0-num1, 0-num2)
    else:
        return num1+multiply(num1,num2-1)
ans='y'
while ans=='y':
    main()
    ans=input('Would you like to run again? (y for yes):')
    

                print('Customer info:')
                print('Name:', cust.get_name())
                print('Age:', cust.get_age())
                print('Phone:', cust.get_phone_number())               
                
                
        











        
n your house?:"))
count=1
sum=0
while count<=rooms:
	answer=input("What is the name of your room:")
	rwidth=float(input("What is the width of your room?"))
	rlength=float(input("What is the length of your room?"))
	area=rwidth*rlength
	total=rwidth*rlength
	print("The area of this room is", str(count), "is", str(area))
	count=count+1
	sum=sum+area
print("The total area of the house is", str(sum))

def main():
    list1=[3,4,5,2]
    result=RecFunc(list1,len(list1))
    print('The result of the recursive function is',result)

def RecFunc(list1,length):
    if length== 0:
        return 1
    else:
        return list1[length-1]*RecFunc(list1, length-1)

main()
    
        

pres=input("Please enter the new President:")
secr=input("Please enter the new Secretary:")
trea=input("Please enter the new Treasurer:")
vp=input("Please enter the new Vice President:")
officers={'President': pres, 'Secretary':secr, 'Treasurer': trea, 'Vice President': vp}
for i in officers:
    print("The new", i, "is "+ str(officers[i]))
    
