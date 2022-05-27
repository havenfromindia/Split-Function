# split function

# This function helps in getting multiple inputs from users. It breaks the given input by the specified separator.
# If a separator is not provided then any white space is separator.
# Any number of white space can be used as a seperator.
# Generally, users use a split() method to split a Python string but one can use it for taking multiple inputs.

# taking in values by specifing the number of inputs (using variables).

# a) Taking two inputs at a time:
a, b = input('enter 2 values : ').split()
print('a is :', a)
print('b is :', b)
# enter the values : hey there
# a is : hey
# b is : there
print(a, b)
# hey there

# b) Taking four inputs at a time:
x, y, c, d = input('enter 4 values : ').split()
print(x, y, c, d)
# are you okay ?
print('d is :', d)

# c) Taking three inputs at a time:
p, q, r = input('enter three values :').split()
print(p, q, r)
# enter three values :16 10 2006
# 16 10 2006

