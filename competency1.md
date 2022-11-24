# WGU

# Task 1
# declare 3 variables with one assignment statement and assign each one an integer value
 
a, b, c = 1, 2, 3

print(a)
print(b)
print(c)
 
# Task 2
# convert each of your previous variables to float objects

print(float(a))
print(float(b))
print(float(c))
 
# Task 3
# convert each of your previous variables to string objects
 
print(str(a))
print(str(b))
print(str(c))
 
# Task 4
# Print the result of dividing 783.56 by 123.2 and ensure that the answer results in an integer
# expected outcome: 6
 
result = int(783.56 / 123.2)
print(result)
 
# Task 5
# Determine if 2019 is a leap year and print the result.
# expected outcome: 3

print(2019 / 4)
 
# Task 6
# Print the calculated length of myFirstString.
# expected outcome: 35

myFirstString = 'I love working with Python so much!'

print(len(myFirstString))
 
# Task 7
# Create a string value and print it with the first letter of each word capitalized using a Python method.
 
MyString7 = ('My name is erin stettler')

print(MyString7.title())
 
# Task 8
# Create a string value and determine if the string consists of only lowercase characters. Print the results.
# expected outcome: True or False

MyString8 = ('I am taking Intro to Programming in Python')

print(MyString8.islower())

 
# Task 9
# Use the given variable to construct a python statement that counts how many times the word pizza is used. Print the final count.
# expected outcome: 3
commercial = 'In the Little Ceasars pizza commercial the character says, "pizza, pizza"!'

print(commercial.count('pizza'))
 
# Task 10
# Use the given username and phone to create a message that lets the user know that you will be calling
# at a specified number for your appointment. Use the format method to insert data into the printed message.
# expected outcome:
# Hi, Allen. I will call you at 888-555-0011 for our appointment.
username = 'Allen'
phone = 8885550011

print('Hi, {}. I will call you at {} for our appointment.'.format(username, phone))
