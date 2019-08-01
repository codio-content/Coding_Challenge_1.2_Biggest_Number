## Skills required
Students will need to be able to:

 - Write conditional statements using IF, ELSE (and ELIF for the extension task)

## Extension
Some students will foresee that the numbers could be equal. They should use ELIF (or equivalent) in their conditional block to handle this.

## Solutions

Not accounting for equal values

    num1 = int(input("Enter number 1: "))
    num2 = int(input("Enter number 2: "))

    if num1 > num2:
      print("Number 1 is the biggest")
    else:
      print("Number 2 is the biggest")
      
      
Allowing for equal values

    num1 = int(input("Enter number 1: "))
    num2 = int(input("Enter number 2: "))

    if num1 > num2:
      print("Number 1 is the biggest")
    elif num2 > num1:
      print("Number 2 is the biggest")
    else:
      print("The numbers are equal")