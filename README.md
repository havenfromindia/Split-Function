# Split-Function
Using split function in input

# change the date of birth function using split

#This function helps in getting multiple inputs from users. It breaks the given input by the specified separator.
# If a separator is not provided then any white space is a separator.
# Generally, users use a split() method to split a Python string but one can use it for taking multiple inputs.


# a) Taking two inputs at a time:

a, b = input("Enter 2 variables").split()

# here in split a space is what seperate 2 inputs and not commas
print("a is:", a)
print("b is:", b)
# Enter 2 values there 'hi there'
# a is: hi
# b is: there
print(a,b)
# 3 4

##************************************************************************

# b) seprating values given using commas( using '  ","  ')
x , y , z = input("Enter variables: ").split(",")
print(x, y, z)
# Enter variables: how,are,you
# how are you

#**************************************************************************

# c) Taking Unlimited Inputs:
#becausing of using this "," the values must be seperated by commas
x = input("Enter variables: ").split(",")
print(x)
# Enter variables: 33,44,amazing,loop,9.8
# ['33', '44', 'amazing', 'loop', '9.8']

# *****************************************************************************

# d) Taking Multiple Inputs As List
x = list(map(int, input("Enter multiple value: ").split()))
print("List of students: ", x)
# Enter multiple value: 67 90 89 54 12 34 09
# List of students:  [67, 90, 89, 54, 12, 34, 9]
