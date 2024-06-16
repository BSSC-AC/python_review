# Selection With Three Or More Outcomes

## Learning Objectives/Goals
Be able to read, comprehend, trace, adapt and create Python code using selection that:
- Uses Boolean conditions
- Uses selection using IF, ELIF and ELSE for more than two situations

## Slide Deck

Lesson slides to introduce concepts and accompany these activities [are here](https://docs.google.com/presentation/d/1niBb3t898D7-rsLkRc4iWNxqxpzyoaS159yuhksag5E/edit?usp=sharing)

## TEACHER NOTES - Selection With Three or More Outcomes

These activities teach students how to use selection that handles output one of three or more different statements.  The indented code below the ‘if’ runs when the condition is true.  The ‘elif’ is short for ‘else if’ - this allows us to add another condition to be checked if the previous one is false.  You can add as many of these as you like defending on how many outcomes you need.  The ‘else’ comes last and is used as a catch all - if the other conditions are false then the computer skips down to the else and runs the indented code there instead. 

To summarise, this code should be written like this:

```
if  condition:
  Code to run if condition above is true.
elif condition:
  Code to run if condition above is true.
```

_As many elifs as necessary (two less than the total number of outcomes - one outcome is covered by the if, another by the else)._
```
else:
  Code to run if all conditions have been checked and found false.
```

NB - you don’t _need_ to include an else at the end of a selection statement, but it is usually good practice, and there’s enough cognitive load in this session already without introducing another element.  I’ve found it useful to teach beginner students that they should always include an else.

## CODE EXAMPLES

Weather advice for three conditions:

```
if weather == “rain”:
	print(“Take your umbrella”)
elif weather == “snow”:
	print(“Take your scarf”)
else:
	print(“No special advice for you”)
```

Weather advice for four conditions:

```
if weather == “rain”:
	print(“Take your umbrella”)
elif weather == “snow”:
	print(“Take your scarf”)
elif weather == “sunny”:
	print(“Take your sunglasses”)
else:
	print(“No special advice for you”)
```

Compare two numbers:
```
if num1 > num2:
  print(str(num1) + " is bigger")
elif num1 <> num2:
  print(str(num2) + " is bigger")
else:
  print("Numbers are the same")
```

### Modify

In the **modify** tasks, students adapt the example code to start to create code of their own.

Make sure that the students add comments to explain what the code does.

## Misconceptions & Errors to watch out for.

Make sure that you check for the following things:

- selection begins with 'if' has as many 'elif's in the middle as you need and end with 'else'
- a colon at the end of each if and else line.
- each branch is indented unsing the TAB key (not just spaces)
- if, elif & else **aren't** indented
- a condition after each 'if' and 'elif'
- no condition after 'else'
- a **double** equals in the condition when chcking that two pieces of data are the same.