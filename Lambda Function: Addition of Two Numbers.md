# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
# Lambda function to add two numbers

add = lambda a, b: a + b

# Input from user
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

# Call the lambda function
result = add(a, b)

print("Sum =", result)
```

## Output
```
Enter first number: 10
Enter second number: 20
Sum = 30
```

## Result
The output has been verified succesfully.
