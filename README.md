- 👋 Hi, I’m @Sibalan
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

def add(p,q):
    return p + q

def subtract(p, q):
    return p - q

def multiply(p, q):
    return p * q
 
def divide(p, q):
    return p / q
 
print("Please select operation.")
print("a.Add")
print("b.Subtract")
print("c.Multiply")
print("d.Divide")
choice = input("please enter choice(a/b/c/d):")
num_1 = int(input("please enter the first number:"))
num_2 = int(input("please enter the second number:"))
 
if choice == 'a':
    print(num_1, "+", num_2, "=",add(num_1,num_2))
                    
 
elif choice == 'b':
    print(num_1, "-", num_2, "=",subtract(num_1,num_2))
                   
 
elif choice == 'c':
    print(num_1, "*", num_2, "=",multiply(num_1, num_2))
                    
 
elif choice == 'd':
    print(num_1, "/", num_2, "=",divide(num_1, num_2))
                    
else:
    print("This is an Invalid input")
