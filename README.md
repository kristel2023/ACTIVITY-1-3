# ACTIVITY-1-3
# Print numbers from 0 to 10 using while loop
num = 0
print("Numbers from 0 to 10:")
while num <= 10:
    print(num)
    num += 1  # Increment the counter

# Print numbers from 10 to 0 using while loop
num = 10
print("\nNumbers from 10 to 0:")
while num >= 0:
    print(num)
    num -= 1  # Decrement the counter

# Initialize variables
total_sum = 0

print("Enter integers (enter 0 to stop):")

# Start while loop
while True:
    num = int(input("Enter a number: "))
    
    if num == 0:  # Stop when user enters 0
        break
    
    if num > 0:   # Only add positive numbers
        total_sum += num

# Display the result
print("\nThe sum of all positive integers entered is:", total_sum)

# Initialize variables
num = 1
product = 1

# While loop to calculate product
while num <= 5:
    product *= num  # Multiply current number
    num += 1       # Increment the number

# Display the result
print("The product of numbers from 1 to 5 is:", product)


