Lists
A list in Python is an ordered collection of items, which can be of any data type.

Basic Operations:

Creating a list: Lists are created using square brackets [].
Adding elements: Elements can be added using the append() method or using list concatenation.
Removing elements: Elements can be removed using the remove() method or by using the del statement.
Modifying elements: Elements in a list can be modified by accessing them using their index and assigning a new value.
Here's an example Python program demonstrating these operations with lists:

python
Copy code
# Creating a list
my_list = [1, 2, 3, 4, 5]

# Adding elements
my_list.append(6)
print("After appending 6:", my_list)

# Removing elements
my_list.remove(3)
print("After removing 3:", my_list)

# Modifying elements
my_list[0] = 10
print("After modifying first element to 10:", my_list)
Dictionary
A dictionary in Python is an unordered collection of key-value pairs.

Basic Operations:

Creating a dictionary: Dictionaries are created using curly braces {} or the dict() constructor.
Adding elements: Elements can be added by assigning a value to a new key.
Removing elements: Elements can be removed using the del statement or the pop() method.
Modifying elements: Elements in a dictionary can be modified by accessing them via their key and assigning a new value.
Here's an example Python program demonstrating these operations with dictionaries:

python
Copy code
# Creating a dictionary
my_dict = {'a': 1, 'b': 2, 'c': 3}

# Adding elements
my_dict['d'] = 4
print("After adding 'd':", my_dict)

# Removing elements
del my_dict['b']
print("After removing 'b':", my_dict)

# Modifying elements
my_dict['a'] = 10
print("After modifying 'a' to 10:", my_dict)
Set
A set in Python is an unordered collection of unique elements.

Basic Operations:

Creating a set: Sets are created using curly braces {} or the set() constructor.
Adding elements: Elements can be added using the add() method.
Removing elements: Elements can be removed using the remove() method.
Modifying elements: Since sets are unordered and contain only unique elements, modification generally involves adding or removing elements.
Here's an example Python program demonstrating these operations with sets:

python
Copy code
# Creating a set
my_set = {1, 2, 3, 4, 5}

# Adding elements
my_set.add(6)
print("After adding 6:", my_set)

# Removing elements
my_set.remove(3)
print("After removing 3:", my_set)

# Note: Sets do not support indexing, so there's no direct modification like lists or dictionaries
Summary
In Python:

Lists are ordered collections of items.
Dictionaries are unordered collections of key-value pairs.
Sets are unordered collections of unique items.
