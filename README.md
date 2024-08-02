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
