# Task Modify

## What’s a **Modify** task?

In the modify tasks, you are given some starter code.
Use the instructions below to make changes to the code.
Comment your changes to explain what you have done.

Adapt the code to:

- Add 'Minecraft' to the start of the list.

- Ask the user to input a number between 0 and 4 and store it in a variable.  Output the item at this position in the list.

- Ask the user to input the name of a video game and store it in a variable.  
  - If this video game is in the list then remove it from the list.
  - If it isn't in the list then add it to the end.

## List Operations - Reference Table

| Output item      | Outputs a single item from the array.                    | print(arrayName\[itemIndex\])<br><br>print(sweets\[3\])                                                                                                                                                                                                                           |
| ---------------- | -------------------------------------------------------- |-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Edit item        | Changes or replaces an item in an array.                 | arrayName\[itemIndex\] = New data<br><br>sweets\[1\] = "Haribo"                                                                                                                                                                                                                   |
| Add an item      | Puts a new item onto the end of the array                | arrayName.append(new data)<br><br>sweets.append("Galaxy")                                                                                                                                                                                                                         |
| Remove an item   | Removes an item from the array                           | arrayName.pop(itemIndex)<br><br>sweets.pop(2)                                                                                                                                                                                                             |                                                                                                                                                                                                                                                              |
| Output all items | Outputs every item in the array one by one using a loop. | for i in range(0, len(arrayName)):<br>&nbsp;&nbsp;&nbsp;&nbsp;print(arrayName\[i\])<br><br>for i in range(0, len(sweets)):<br>&nbsp;&nbsp;&nbsp;&nbsp;print(arrayName\[i\])<br><br><br>OR<br><br>#This is a nice built in Python shortcut, but you need to know how to do the for loop version for the exam.<br><br>print(sweets) |

## Help! My code doesn't work
Make sure that you check for the following things:
- The list name is identical everywhere it is used (capitals matter)
- List index is surrounded by **square** brackets
- List indexing starts at **zero** - are you counting properly?