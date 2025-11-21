# 1 Character to Number Conversion :
char = input("Enter a single character: ")
number = ord(char)
print(f"The Unicode number for '{char}' is {number}")

# 2 Boolean Values and Operators :
a = 10
b = 20
print(a == b)   
print(a < b)  

# 3 if statement
num = int(input("Enter a number: "))
if num > 0:
    print("Positive number")  

# if-else statement
if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")

# if-elif-else statement
if num > 0:
    print("Number is positive")
elif num == 0:
    print("Number is zero")
else:
    print("Number is negative")

# 4 Iteration Statements

# while loop:
count = 0
while count < 3:
    print("while loop count:", count)
    count += 1

# for loop: iterates over a sequence (list here)
for i in range(3):
    print("for loop iteration:", i)

# Using break, continue, pass in a loop
for num in range(5):
    if num == 3:
        break  # exits the loop completely
    if num == 1:
        continue  # skips to the next iteration
    if num == 2:
        pass  # does nothing; placeholder
    print("Control statements num:", num)
