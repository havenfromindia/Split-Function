# Split-Function
Using split function in input


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
# With Map Function:
# Used Map Function (Optional) to convert thy input into an integer.
x = list(input("Enter multiple value: ").split())
print("List of students: ", x)
# Enter multiple value: hey 78 amazing person 2021
# List of students:  ['hey', '78', 'amazing', 'person', '2021']

# -----------------------------------------------------------------------------------------------------

# Without Map Function:
x = list(map(int, input("Enter multiple value: ").split()))
print("List of students: ", x)
# Enter multiple value: 67 90 89 54 12 34 09
# List of students:  [67, 90, 89, 54, 12, 34, 9]

# -----------------------------------------------------------------------------------------------------

# Taking Multiple Inputs at a time:
x = [int(x) for x in input().split()]
print("Number of list is: ", x)
# 43 12 34 67 09 653 2321 12
# Number of list is:  [43, 12, 34, 67, 9, 653, 2321, 12]

# **********************************************************************************

# Using Strip() method
# strip() is an inbuilt function that returns a copy of the string ,
# with both leading and trailing characters removed (based on the string argument passed)
# string.strip([chars]) ,
# chars — a string specifying the set of characters to be removed.
# If the optional chars parameter is not given, all leading and trailing whitespaces are removed from the string.

string = " the King has the largest army in the entire world the"
# prints the string after removing "the" from beginning and end
print(string.strip(" the"))
# King has the largest army in the entire world

string = " .the King has the largest army in the entire world the."
# prints the string after removing ".the" from beginning and end
print(string.strip(" .the"))
# King has the largest army in the entire world

# The strip method can make your input clean removing unnecessary inputs.

# ************************************************************************************
