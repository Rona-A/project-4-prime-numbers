# project-4-prime-numbers
# Function to check if a number is prime
"""def is_prime(num):
    if num <= 1:
        return False
    if num == 2:
        return True  # 2 is a prime number
    if num % 2 == 0:
        return False  # Other even numbers are not prime

    # Check for odd factors from 3 up to sqrt(num)
    divisor = 3
    while divisor * divisor <= num:
        if num % divisor == 0:
            return False
        divisor += 2
    return True

# Using for loop to find and print prime numbers between 1 and 100
print("Prime numbers between 1 and 100:")
for number in range(1, 101):
    if is_prime(number):
        print(number, end=" ")

print("\n")
# Using while loop to find and print prime numbers between 1 and 100
print("Prime numbers between 1 and 100 (using while loop):")
number = 1
while number <= 100:
    if is_prime(number):
        print(number, end=" ")
    number += 1"""


#while loop
"""num = 2
while num <= 100:
    prime = True
    divisor = 2
    while divisor <= num//2:
        if num % divisor == 0:
            prime = False
            break
        divisor += 1
    if prime:
        print(num)
    num += 1"""

#FOR LOOP
for num in range(2, 101):
     prime = True
     for divisor in range(2, num//2 +1):
         if num % divisor == 0:
             prime = False
     if prime:
         print(num)
