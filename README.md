# Lab3
#
# calculator
#

sum= 0

# 1. input
x1 = input("enter x1: ")
x2 = input("enter x2: ")
op = input("enter operator: ")

# 2. process
if op == "+":
   sum = int(x1) + int(x2)
elif op == "-":
   sum = int(x1) - int(x2)
elif op == "*":
   sum = int(x1) * int(x2)
elif op == "/":
   sum = int(x1) / int(x2)

# 3. output
print(f"sum: {sum}") 