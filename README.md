# split function

# This function helps in getting multiple inputs from users. It breaks the given input by the specified separator.
# If a separator is not provided then any white space is separator.
# Any number of white space can be used as a seperator.
# Generally, users use a split() method to split a Python string but one can use it for taking multiple inputs.

# taking in values by specifing the number of inputs (using variables).

# 2) Taking Unlimited Inputs:
unlimited = input('enter the values for the list : ').split()
print(unlimited)
# enter the values for the list : 34 23 liquid gwen
# ['34', '23', 'liquid', 'gwen']

# *************************************************************************************************************
# if only a single variable is provided then the single variable can store more than 1 value.
# if more than 2 variables are given, only a single value will be assigned to 1 variable based on seperator.
