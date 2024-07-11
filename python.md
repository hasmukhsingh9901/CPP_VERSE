# Python Methods

## 1. String Methods
- `str.lower()`: Converts all characters in the string to lowercase.
- `str.upper()`: Converts all characters in the string to uppercase.
- `str.strip()`: Removes any leading and trailing whitespaces from the string.
- `str.split()`: Splits the string into a list based on a delimiter.
- `str.join()`: Joins a list of strings into a single string with a specified separator.
- `str.replace(old, new)`: Replaces occurrences of a substring with another substring.
- `str.find(sub)`: Finds the first occurrence of a substring.
- `str.format()`: Formats the string using placeholders.

## 2. List Methods
- `list.append(x)`: Adds an element `x` to the end of the list.
- `list.extend(iterable)`: Extends the list by appending elements from an iterable.
- `list.insert(i, x)`: Inserts an element `x` at a specified position `i`.
- `list.remove(x)`: Removes the first occurrence of an element `x`.
- `list.pop([i])`: Removes and returns the element at the specified position.
- `list.clear()`: Removes all elements from the list.
- `list.index(x)`: Returns the index of the first occurrence of an element `x`.
- `list.count(x)`: Returns the number of occurrences of an element `x`.
- `list.sort()`: Sorts the list in ascending order.
- `list.reverse()`: Reverses the order of the list.

## 3. Dictionary Methods
- `dict.keys()`: Returns a view object with all the keys in the dictionary.
- `dict.values()`: Returns a view object with all the values in the dictionary.
- `dict.items()`: Returns a view object with all the key-value pairs in the dictionary.
- `dict.get(key)`: Returns the value associated with a key.
- `dict.update([other])`: Updates the dictionary with key-value pairs from another dictionary or an iterable.
- `dict.pop(key[, default])`: Removes and returns the value associated with a key.
- `dict.popitem()`: Removes and returns the last key-value pair.
- `dict.clear()`: Removes all elements from the dictionary.

## 4. Set Methods
- `set.add(x)`: Adds an element `x` to the set.
- `set.update(iterable)`: Updates the set with elements from an iterable.
- `set.remove(x)`: Removes an element `x` from the set, raises a KeyError if the element is not present.
- `set.discard(x)`: Removes an element `x` from the set, does not raise an error if the element is not present.
- `set.pop()`: Removes and returns an arbitrary element from the set.
- `set.clear()`: Removes all elements from the set.
- `set.union(*others)`: Returns the union of sets.
- `set.intersection(*others)`: Returns the intersection of sets.
- `set.difference(*others)`: Returns the difference of sets.
- `set.symmetric_difference(other)`: Returns the symmetric difference of sets.

## 5. Built-in Functions
- `len()`: Returns the length of an object.
- `type()`: Returns the type of an object.
- `isinstance()`: Checks if an object is an instance of a class or a tuple of classes.
- `id()`: Returns the identity of an object.
- `sorted()`: Returns a sorted list from the elements of an iterable.
- `sum()`: Returns the sum of an iterable's elements.
- `min()`: Returns the smallest item in an iterable.
- `max()`: Returns the largest item in an iterable.
- `abs()`: Returns the absolute value of a number.
- `round()`: Rounds a number to a specified number of decimal places.
