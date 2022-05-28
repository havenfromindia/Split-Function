# split function

# This function helps in getting multiple inputs from users. It breaks the given input by the specified separator.
# If a separator is not provided then any white space is separator.
# Any number of white space can be used as a seperator.
# Generally, users use a split() method to split a Python string but one can use it for taking multiple inputs.

# separator: This is a delimiter. The string splits at this specified separator.
#  If is not provided then any white space is a separator.

# Seperator is what which is mentioned inside the double cord. In this case it is a comma.
# White spaces will no longer remain to be the seperator

a, b = input('enter 2 values : ').split()
print(a, b)
a, b = input('enter 2 values : ').split(",")
print(a, b)
# enter 2 values : we build
# we build
# enter 2 values : we build,none
# we build none

# here spaces wont be recognised as seperators
x, y, z = input('enter 3 values : ').split(",")
print(x, y, z)
# enter 3 values : we, build ,the      world
# we  build  the      world

# *****************************************************************************************************

# can seperator be anything else other than commas
value, given = input('enter 2 values : ').split("&")
print(value, given)
# enter 2 values : we*won
# we won

value, given = input('enter 2 values : ').split("can")
print(value, given)
# enter 2 values : howcanyou
# how you

# so what ever inside the double cords are seperators

# *******************************************************************************
# project : seperator + unlimited inputs + for loop
unknown = input('enter the values in the list : ').split(',')
print(unknown)
for i in unknown:
    print(i)
# enter the values in the list : 10,45,34,78,57,78,miles,gwen
# ['10', '45', '34', '78', '57', '78', 'miles', 'gwen']
# 10
# 45
# 34
# 78
# 57
# 78
# miles
# gwen    

