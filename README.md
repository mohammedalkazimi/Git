for num in range(1, 21):
    print(num)
    for num in range(2, 21, 2):
    print(num)
    # Ask the user to enter the upper limit
upper_limit = int(input("Enter the upper limit: "))

total_sum = 0
even_sum = 0
odd_sum = 0

# Calculate sums
for number in range(1, upper_limit + 1):
    total_sum += number

    if number % 2 == 0:
        even_sum += number
    else:
        odd_sum += number

# Display results
print("Sum of all numbers from 1 to", upper_limit, "=", total_sum)
print("Sum of even numbers =", even_sum)
print("Sum of odd numbers =", odd_sum)

# Additional example: Sum from 1 to 50
sum_50 = 0
for number in range(1, 51):
    sum_50 += number

print("Sum of numbers from 1 to 50 =", sum_50) 
# Ask the user for two numbers
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

# Ask the user for the maximum multiplier
max_multiplier = int(input("Enter the maximum multiplier: "))

print("\nMultiplication Table for", num1)
print("-" * 30)

for i in range(1, max_multiplier + 1):
    print(f"{num1:2} x {i:2} = {num1 * i:3}")

print("\nMultiplication Table for", num2)
print("-" * 30)

for i in range(1, max_multiplier + 1):
    print(f"{num2:2} x {i:2} = {num2 * i:3}")
name = input("Enter your name: ")

i = 0
while i < len(name):
    print(i + 1, name[i].upper())
    i += 1

print("Total characters:", len(name))

i = len(name) - 1
while i >= 0:
    print(name[i].upper())
    i -= 1
