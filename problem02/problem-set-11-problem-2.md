# Module 7 - Problem Set No. 11 Problem 2

## Calculate Property Tax

**IMPORTANT - PROVIDE AN IPO (Inputs, Processes, and Output) AT THE TOP OF EACH PROGRAM USING COMMENTS.**

- Enter your name at the top of the program where it says **YOUR NAME**
- At the top of each program, including a section of comments that identifies all of the inputs, processes, and outputs for the program.
- Include comments within your code explaining what the code is doing. - You don't need to comment every line.
- You must use coding techniques covered in Chapters 1, 2, 3, 5, 6, 7 and 8 in your solutions.

## Instructions

You have been asked to develop a Python program that will assist a clerk who works at the Clark County Assessors Office that will assist them calculating property tax for a given list of properties. The list is printed out by the clerk on paper. Don't use a Python list for this problem. It's not needed. :-).

The calculation used:

```text
property tax = property value x 0.0170
```

In your interview with the tax clerk Bruce, you learn that each peroperty ia assigned a lot number, and all lot numbers are numbered 1 or greater.

You decied to write a while loop that uses the number 0 as a **sentienl value**. During each loop iteration, the program will ask the clerk to enter either a property's lot number, or 0 to end.

Your program should ask for a lot number and the print out the proeprty tax if the lot number is greater than 0.

You will need to keep processing lots until the clerk is done using 0 as the sentinal for the lot number.

Name your function **taxProcessor()**.
