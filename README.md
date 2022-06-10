# split function

# This function helps in getting multiple inputs from users. It breaks the given input by the specified separator.
# If a separator is not provided then any white space is separator.
# Any number of white space can be used as a seperator.
# Generally, users use a split() method to split a Python string but one can use it for taking multiple inputs.

# Using Strip() method
# string.strip([chars])

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

# using this function we can only remove chars from start & end. never from midle
simple = "we will do this now "
print(simple.strip("we will now "))
# do this

simple = "we will do this now itself"
print(simple.strip("we will now "))
# do this now itself
# it print now because 'now' is not a character from start or end but from midle

simple = "# we will do this now "
print(simple.strip("we will > now yu # $ % "))
# used to remove unneccisary items

