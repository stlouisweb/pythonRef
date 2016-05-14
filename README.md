# Python Reference

## The Print() function
print() is a built-in function, that sends the value of what you place in between the parentheses to stdout.

>stdout = standard output, this means that you'll see the values returned in the interpreter window.

```
>>> print('Hello')
Hello
```

## Mathematical Operators
- \+ = Addition
- \- = Subtraction
- \- = Multiplication
- / = Division

 ```
>>> 2 + 2 * 5 - 2
12
 ```

## Variable Assignment
Assign values to variable names like so:
- variable_name = variable_value

```
>>> my_variable = 'Hello'
>>> print(my_variable)
Hello
```

### String variable
- str = 'my string'
- str = "my string"
- str = 'I/'m a teapot'
- str = '''This is a multi-line
string, you can use multiple lines and don't need to worry about escaping'''

> Escaping is adding a / forward slash before a quote mark or other character with special meaning to python, so that it knows to print the actual character and not do something else

> Multi-line strings are marked by triple quotes ('''), and do the escaping automagically

### Number variable
- number = 7

### List variable
- list = ['item1', 'item2', 'item3']

> Lists are collections of values contained within square brackets

## Working with Lists

Create a List:    
```
>>> my_list = ['earth', 'wind', 'fire']
>>> print(my_list)
['earth', 'wind', 'fire']
```
Select a single item in the list:
```
>>>print(mylist[0])
earth
```
0 is the index of the item you want to select:
- 0 = earth
- 1 = wind
- 2 = fire

Add an item to a list with the `append` function:
```
>>> my_list.append('water')
>>> print(my_list)
['earth', 'wind', 'fire', 'water']
```

Remove an item from a list with the `del` (delete) command:
```
>>> del my_list[3]
>>> print(my_list)
['earth', 'wind', 'fire']
```

Change an item in a list at the specified index:
```
>>> my_list[2] = 'water'
>>> print(my_list)
['earth', 'wind', 'water']
```

## List Joins
You can combine two lists into one with the `+` sign
```
>>> list1 = 1, 2, 3
>>> list2 = 'cat', 'dog', 'fish'
>>> print(list1 + list2)
[1, 2, 3, 'cat', 'dog', 'fish']
```

## Multiplying Strings and Lists
```
>>> print(a * 5)
aaaaa
>>> list = [0, 1]
>>> print(list * 5)
[0, 1, 0, 1, 0, 1, 0, 1, 0, 1]
```

## Tuples
Tuples are like lists that use parentheses instead of brackets
```
>>> my_tuple = (1, 2, 3)
>>> print(my_tuple)
(1, 2, 3)
```

Unlike lists, tuples can not be modified after they are created. This is known as immutable data, you can not change it but you can use it to create new things.

## Maps

map = dict = dictionary
