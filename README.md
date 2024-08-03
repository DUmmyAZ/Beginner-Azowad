# Beginner-Azowad
Learning coding as well as saving it for others :3


#start
#Ask user for their name
name = input("whats your name? ")

#say hello to user
print('Hello, "friend" ' +name) #connecting multiple arguments
print("Hello,",name, sep='')
print("Hello, ", end="")
print(name)
"""
comment 
"""
#escape characters and double or single quotation
"""
txt = "We are the so-called \"Vikings\" from the north."
print(txt)
print("hello, \"friend\"")
print('Hello, "friend"')
print('Hello, "friend"')
#format string or "f" str
print(f"Hello, {name}")
text = "abir"
print(f"Hello, \"dear\" {text}" ) 
"""
#remove whitespace from str
username = input("Username  please: ")
username = username.strip()
print("The name of the user is :",username)
print(f"The name of the user is: {username}")
#capitalize Username
username = username.capitalize()
print(f"User is called {username}")

#title
username = username.title()
print(f"User is {username}")

""" #ALL IN ONE
tname = input("")
tname = tname.strip()
tname = tname.capitalize()
tname = tname.title()
print(f"Tname is {tname}")
"""
#Remove whitespace from str and title user's name 
username = username.strip().title()
print(f"username is {username}")
#simpler procedure
u_name = input("Write your name: ").strip().title()
print(f"hello, {u_name}")

#Split user's name into first and last name
first, last = username.split(" ")
print(f"Your first name is {first} right?" )
print(f"your last name is {last} right?")


#def 
def hello(to="World"):
    print("hello", to)
hello()
name = input("What's Your name? ").title()
hello(name)

#stabdard way
#def main(): #just to make it easier for anyone to understnad
    name = input("whats your name? ")
    hello(name)
    
def hello(to="world"):
    print("hello ",to)
main()

#name = input("Whats Your Name? ").strip().title()
print(f"Hello, {name}")
"""first,last = name.split(" ")
print(f"First name is {first}")
print(f"Last name is {last}")"""   
a = input("Dial a digit : ")
b = input("Dial another digit : ")
x = float(a)+float(b)
print(f"{x:,}")
m = float(input("Enter the value of m: "))
n = float(input("Enter the value of n : "))
o = round( m/n, 2 )
print(o)
def main():
    name = input("Whats your name sir : ")
    Hello(name)
def Hello(to="world"):
    print("Hello",to)
main()

#Calc

#int
x = input("Enter the value of x : ")
y = input("Enter the value of y : ")
z = int(x) + int(y)
print(z)
#standard way
p = int(input("Whats p? "))
q = int(input("whats q? "))
print(p + q)
#complex procedure
print(int(input("Value of A : ")) + int(input("Value of B : ")))
#float
m = float(input("Value of m : "))
n = float(input("Value of n : "))
o = (m + n)
o = round(m + n) #it will round the number up to the nearest integer
#print(o)
print(f"{o:,}")#just to format the number.
"""m = input("Dial the value of m : ")
n = input("Dial the value of n : ")
print(float(m) + float(n))
#divide
#o = (m/n)
o = round(m/n,2)#used 2 after "," just to set how many digits will be shown after the decimal point
print(o)"""
#different way
o = m / n
print(f"{o:.2f}")

#def main():
    p = int(input("Value of p : "))
    print(f"p squared is : ",square(p))
def square(q):
    return q*q
main()

#def main():
    x = int(input("Enter a value for x :"))
    print(f"x square is :", square(x))

def square(n):
    return n*n
main()
squared = 2 ** 2
print(squared)

#def main():
    p = int(input("value of p : "))
    print(f"p squared is : ",squared(p))
def squared(n):
    return pow(n, 2)
main()


#compare.py
x = int(input("What's x? "))
y = int(input("What's y? "))

if x>y:
    print("x is greater than y")
elif x<y:
    print("x is less than y")
else :
    print("x equals to y")
    
#or function
p = int(input("Enter digit for p "))
q = int(input("Enter digit for q "))
if p>q or p<q :
    print("x isnt equals to y")
else :
    print("x equals to y")
    
#simple way
a = int(input("Whats a? "))
b = int(input("whats b? "))
if a!=b:
    print("a isnt equal to b")
else: 
    print("a equals to b")

#GRADE
score = int(input("Score/Mark: "))
if score>=90 and score<=100:
    print("Grade : A")
elif score>=80 and score<90:
    print("Grade : B")
elif score>=70 and score<80:
    print("Grade : C")
elif score>=60 and score<70:
    print("Grade : D")
elif score>=50 and score<60:
    print("Grade E")
else:
    print("Grade : F")

#easy way: 
mark = int(input("Mark : "))
if 90<=mark< 100:
    print("Grade : A")
elif 80<=mark<90:
    print("Grade : B")
elif 70<mark<80:
    print("Grade : C")
elif 60<mark<70:
    print("Grade : D")
elif 50<mark<60:
    print("Grade E")
else:
    print("Grade : F")
    
#another way
number = int(input("Number: "))
if number >= 90:
    print("Grade : A ")
if number >= 80:
    print("Grade : B ")
if number >= 70:
    print("Grade : C ")
if number >= 60:
    print("Grade : D ")
if number >= 50:
    print("Grade : E ")
else :
    print("Grade : F ")


#Module
x = int(input("Whats x? "))

if x % 2 == 0:
    print(" The number is Even")
else:
    print("The number is Odd")
    
 
 #by fuction def
def main():
    a = int(input("Whats a? "))
    if is_even(a):
        print("Even")
    else :
        print("Odd")
def is_even(n):
    if n%2==0:
        return True
    else:
        return False
main()

#more pythonic way
def main():
    p = int(input("Whats p? "))
    if is_eeven(p):
        print("Even")
    else :
        print("Odd")
def is_eeven(n):
    return True if n%2 == 0 else False
main()

#better / elegant way
def main():
    b = int(input("Whats b? "))
    if is_even(b):
        print("Even")
    else :
        print("Odd")
def iss_even(n):
    return n%2==0
main()


##Harrypotter Based
name = input("What's Your name? ").capitalize()

if name=="Harry" or name=="Hermoine" or name=="Ron":
    print("Gryffindor")
elif name=="Draco":
    print("Slytherin")
else:
    print("Who?")
    
#mactch
name = input("Whats your name? ").capitalize()
match name:
    case "Harry" | "Hermione" | "Ron":
        print("Gryffindor")
    case "Draco":
        print("Slytherin")
    case _:
        print("who?")

#*LOOP
x = 3
while x != 0:
    print("meow")
    x = x-1
    
i = 1
while i < 6:
    print("Hello")
    i +=1 
    
p = 3
while p!=0:
    print("Meow")
    p = p-1
    
q = 1
while q<6:
    print("HI!")
    q = q+1
    #or q +=1
