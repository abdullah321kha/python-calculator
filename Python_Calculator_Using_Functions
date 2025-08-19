# 1. Calculator:
def add (x,y):
  return x+y
def sub(x,y):
  return x-y
def mul(x,y):
  return x*y
def division(x,y):
  if y==0:
    print("Can't divided by zero!")
  else:
      return x/y
def mod(x,y):
  return x%y
def expo(x,y):
  return x**y

def calculator():
  while True:
    print("--------Simple Calculator------")
    print("1. Addition ")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division ")
    print("5. MOD:")
    print("6. Exponent")
    print("7. Exit")

    choose=input("Enter the Choise (1-7):")
    if choose =="7":
        print(" Exit: Thanks for Using the Calculator!!")
        break

    elif choose in ["1","2","3","4","5","6"]:
      x=float(input("input the 1st number:"))
      y=float(input("input the 2nd number:"))

      if choose=="1":
        return add(x,y)
      elif choose=="2":
        return sub(x,y)
      elif choose=="3":
        return mul(x,y)
      elif choose=="4":
        return division(x,y)
      elif choose=="5":
        return mod(x,y)
      elif choose=="6":
        return expo(x,y)
      else:
        print("Invalid input!!")
calculator()





