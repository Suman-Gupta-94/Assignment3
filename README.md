#ASSIGNEMENT3
#Task1:calculate factorial using a function

def factorial_recursive(n): #This is the actual function code
    # that implements the recursive algorithm for calculating factorials
  if n == 0 :  # Base case: Factorial of 0 is 1
    return 1
  else:
      return n * factorial_recursive(n - 1)  # Recursive case: n * factorial(n-1)
# Example usage
# taking input from user using int and integer value so use int first
number = int(input("Enter a number : "))
result = factorial_recursive(number) # in def function always need to assign to result for getting output
print("Factorial of " + str(number) + " is : "+ str(result))

#task2
#using tha math module for calculation
#import math #Import math module
import math
# Get user input for the number
number = int(input("Enter a number: "))

# Calculate and print the square root
square_root = math.sqrt(number) #called math function math.sqrt() and store in square_root
print("The square root of " + str(number) + " is : "+ str(square_root)) #printing output after adding str and int

# Calculate and print the natural logarithm
natural_log = math.log(number) #called math function math.log() and store in variable
print(f"Natural logarithm of {number}:{natural_log}") #print as above but using f string this time
# Calculate and print the sine
sine_value = math.sin(number) #called math function math.sin() and store in variable
print("Sine of " + str(number)+ " is :"+ str(sine_value)) # print without f string use
