## NAME:YUGESH K C
## REG NO:111923AI01118
## DEPARTMENT:B.TECH (AI&DS)
# TASK 1-CALCULATOR USING PYTHON 

## PROGRAM:
```
def add(n1, n2):
    return n1 + n2

def sub(n1, n2):
    return n1 - n2

def mul(n1, n2):
    return n1 * n2

def div(n1, n2):
    return n1 / n2

print("Please select operation -\n"
      "1. Add\n"
      "2. Subtract\n"
      "3. Multiply\n"
      "4. Divide\n")

sel = int(input("Select operation (1-4): "))

n1 = int(input("Enter first number: "))
n2 = int(input("Enter second number: "))

if sel == 1:
    print(n1, "+", n2, "=", add(n1, n2))
elif sel == 2:
    print(n1, "-", n2, "=", sub(n1, n2))
elif sel == 3:
    print(n1, "*", n2, "=", mul(n1, n2))
elif sel == 4:
    print(n1, "/", n2, "=", div(n1, n2))
else:
    print("Invalid input")

## OUTPUT:
![Screenshot 2025-04-29 211001](https://github.com/user-attachments/assets/c5b3d11d-6b22-4433-ae28-0d6f144e3a64)
![Screenshot 2025-04-29 211041](https://github.com/user-attachments/assets/acb99332-9e06-45ac-be1d-baf7e9b4015b)

## RESULT:THE CODE HAS BEEN EXECUTED SUCCESSFULLY



```
