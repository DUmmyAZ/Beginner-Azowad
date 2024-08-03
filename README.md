# Beginner-Azowad
Learning coding as well as saving it for others :3


#start
name = input("Whats Your Name? ").strip().title()
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
def main():
    p = int(input("Value of p : "))
    print(f"p squared is : ",square(p))
def square(q):
    return q*q
main()

def main():
    x = int(input("Enter a value for x :"))
    print(f"x square is :", square(x))

def square(n):
    return n*n
main()
squared = 2 ** 2
print(squared)

def main():
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
