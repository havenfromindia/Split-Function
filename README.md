# split function

# This function helps in getting multiple inputs from users. It breaks the given input by the specified separator.
# If a separator is not provided then any white space is separator.
# Any number of white space can be used as a seperator.
# Generally, users use a split() method to split a Python string but one can use it for taking multiple inputs.

# using ","
# split(",") is used when the seperator is not a space but is a comma

a, b = input('enter 2 values : ').split()
print(a, b)
a, b = input('enter 2 values : ').split(",")
print(a, b)
# enter 2 values : we build
# we build
# enter 2 values : we build,none
# we build none

