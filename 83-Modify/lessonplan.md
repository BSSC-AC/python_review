# Lists
## Learning Objectives/Goals
- Outputs one item from a list
- Outputs a whole list
- Changes an item in a list
- Adds an item to a list
- Removes an item from a list

### Slide deck

Slides to accompany these activities [are here](https://docs.google.com/presentation/d/1_LN6DYLdyRVqY7HxVd7f4l20snyX9joHRXMBGiBYM-g/edit?usp=sharing)

## TEACHER NOTES - Lists

A list is an example of a ‘[data structure](https://www.geeksforgeeks.org/data-structures/)’.  This is the name for a number of different programming techniques used to organise and manipulate data in programs.

So far to store data in the program we have used variables, which hold one piece of data and use an identifier (variable name) to represent it in the code.

Lists work in the same way as variables, but they store multiple items of data using one identifier.

Lists are created in Python like this:


```
countries = ["UK", "USA", "Chad", "Australia", "Thailand"]

primeNumbers = [1,3,5,7,11,13]
```


Notice that the list containing string (text) data has each item in speech marks.  The list containing integer (whole number) data doesn’t need them.

To identify individual items in a list, the data is **indexed **(given a number).  Indexing starts at 0, meaning that the first item in a list will be number 0, the second number 1 and so on.


## Lists - Key Concepts

You may hear lists referred to as ‘arrays’ in other programming languages.  There are small differences but at this stage we will treat them as essentially the same thing.

A list can store multiple items of data.

Items in a list are surrounded by square brackets.  Each item is separated by a comma.

Lists are indexed - each item is given a numerical position in the list.

Lists are named in the same way as variables - the programmer decides what they are called.  Using [camel case](https://en.wikipedia.org/wiki/Camel_case) is best practice

Indexing starts at 0, students often forget this as they are in the habit of starting to count with 1.

A list is changeable - each individual item can be edited, added or removed. Extra items can be added to the list.

A list allows duplicate items.


## Output From Lists


#### TEACHER NOTES 

The `print `command is used to output data from lists, just like it is to output from a variable.


##### Output One Item From A List

To output one item, use print followed by square brackets with the item’s index number.  Eg: 
```
primeNumbers = [1,3,5,7,11,13]

print(primeNumbers[0])
```
This would print ‘1’ from the primeNumbers list, as that is the data at index 0.


```
countries = ["UK", "USA", "Chad", "Australia", "Thailand"]
print(countries[2])
```


This would print ‘Chad’ from the countries list, as that is the data at index 2.


##### Output Every Item In A List

Python makes it simple to output a whole list like this:
```
print(primeNumbers)
```

This code actually uses a loop to go through each item in the list one by one printing them to the console, but this complexity is hidden behind the scenes.


##### Let The User Choose Which Item To Output

To do this, we get the user to input a number and store it in a variable.

In the print statement, replace the number in square brackets with this variable.
```
num1 = input()

print(countries[num1])
```


## Assigning To Lists


#### TEACHER NOTES 

Data in lists can be edited in the same way that data in a variable can.

Let’s use the ‘countries’ list from earlier in this document as an example:


```
countries = ["UK", "USA", "Chad", "Australia", "Thailand"]
```


The = symbol is used to assign new data. Eg this code **replaces **the ‘Australia’ in the ‘countries’ list with ‘Mexico’.


```
countries[3] = "Mexico"
```


This code concatenates (joins) ‘ingdom’ to the end of ‘UK’. countries[0] will now contain ‘UKingdom’ _(not a great example I know, but it works)_.


```
countries[0] = countries[0] + "ingdom"
```


Now let’s use the primeNumbers list to see some maths examples. This list contains integers so we can do maths with them.


```
primeNumbers = [1,3,5,7,11,13]
```


This code adds one to the first item in the list.  primeNumbers[1] will now contain ‘2’.
```
primeNumbers[0] +=1
```

This code multiplies the second & third items in the list and stores the result in the ‘total’ variable. total will now contain ‘15’.
```
total = primeNumbers[1] * primeNumbers[2]
```

This code subtracts the fourth from the fifth item in the list and stores the result in the first position. primeNumbers[0] will now contain ‘2’.
```
primeNumbers[0] = primeNumbers[4] - primeNumbers[3]
```


## Adding To & Removing From Lists


#### TEACHER NOTES 

These activities look at how we add and remove items from a list.  There are two different methods of doing each of these tasks, and they work in slightly different ways.  The code for them is:

**Adding Items**
```
listName.append("item")
``` 
adds an item to the end of the list.
```
listName.insert(positionNumber, "item")
```
inserts the item at the position given in the brackets. The number comes first, then a comma, then the item.

**Removing Items**

```
listName.remove("item")
```
searches through the list and removes the item in brackets.
```
listName.pop()
```
removes the last item in the list.


## Checking To See If An Item Is In The List

Python makes it really easy to check if an item is in a list.  This is where we can start to combine what we’ve previously learned about selection with lists.  The code for this is:

```
if "item" in listName:
	Run this code if condition is true
```

## Modify

In the **modify** tasks, students adapt the example code to start to create code of their own.

Make sure that the students add comments to explain what the code does.
## Misconceptions & Errors to watch out for.

Make sure that you check for the following things:

- The list name is identical everywhere it is used (capitals matter)
- List index is surrounded by **square** brackets
- List indexing starts at **zero** - are you counting properly?