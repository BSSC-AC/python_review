# Calculations

In this topic students learn how to perfrom simple calculations using fixed numbers, numbers stored in variables and numbers input by the user.

## Learning Objectives/Goals

Be able to read, comprehend, trace, adapt and create Python code using selection that:
- Performs simple maths (addition, subtraction, multiplication, division and integer division) using fixed numbers
- Performs simple maths using numbers stored in variables
- Converts strings to integers
- Gets number input and uses it in calculations

## Slide Deck

[The slide deck for this topic can be found here]
(https://docs.google.com/presentation/d/1choFBbf7jyjNm-h37Z4Qyo1xOVVTj0W6mj6PCLRjbYw/edit?usp=sharing)

## TEACHER NOTES

This unit  looks at how computers do basic maths.  This is a process (it happens ‘inside’ the computer).  

We start off by learning about the operators used for simple maths.  Multiplication & division use different operators to paper based maths.  We also see the + operator used for another purpose here as well.

/ is used for division, but it returns a decimal result (known as a **float**).  Python also lets us use // to perform **floor (integer) division **- where it ignores any decimal and just returns the whole number part of the answer (known as an integer, or int).

The tasks increase the complexity by replacing numbers in the code with variables, and then variables assigned using input - this requires **casting**.

#### Casting

Input in python is always taken as **strings** (text), however ccalculations require the data to be in **integer** (whole number) or **float** (decimal number) form.  To convert the data to the right format on input, **casting** is used.

## CODE EXAMPLES

Addition
```
5 + 4
```

Subtraction
```
5 - 4
```

Multiplication
```
5 * 4
```

Division
```
5 / 4
```

Integer Division - Only returns the whole number part of the answer
```
5 // 4
```
Converts input to integer
```
variable = int(input())
```
Converts input to float
```
variable = float(input())
```

## PRIMM Task - Modify

In the **modify** tasks, students adapt the example code to start to create code of their own.

Make sure that the students add comments to explain what the code does.


## Errors & Misconceptions To Watch Out For

Make sure that you check for the following things:

- you have typed the variable name **exactly** the same (including caps), every time
- There is a variable on the **left** of each assignment
- You have used a single **=** for assignment
- You have used the correct **operator**
    - <pre>+ addition
    - <pre>- subtraction
    - <pre>* multiplication
    - <pre>/ decimal division (gives numbers after the decimal point)
    - <pre>// integer division (just gives the whole number part of the answer)
- You have remembered the brackets after input:
    - <pre> input()