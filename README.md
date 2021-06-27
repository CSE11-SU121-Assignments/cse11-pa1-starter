# CSE 11 Programming Assignment 1

### Due Date: Thursday, July 1, 11:59PM Pacific Time

## Learning Goals
- Write functions that take integer parameters and return integer results.
- Practice using design recipes

## Collaboration
Different assignments in this course have different collaboration policies. On this assignment, you can collaborate with **anyone in the course**, including **sharing code**. In your submission, give credit to all students and course staff who helped you with this assignment by noting their name and how you used their ideas or work. Note that using someone's work without giving credit to them is a violation of academic integrity.

## Process
- You can download the starter code for this assignment by downloading this repository and navigating to the ```pa1``` folder. You can reference [this document](https://github.com/CSE11-SP21-Assignments/cse11-sp21-pa0.5-Setup-starter/blob/main/Instructions%20for%20setting%20up%20Java%20on%20your%20own%20machine.pdf) and Discussion 1 for details on setting up your development environment.
- You will write your code in DesignRecipeExamples.java. You can run the code to test it yourself with:

    Mac and CloudLabs: ```./run DesignRecipeExamples```
    Windows:         ```.\run.bat DesignRecipeExamples```
- For problem 3 and 4, you will use the following design recipe:
    1. Write the method header
    2. Write a short comment documenting the method (including assumptions, like if a parameter should take values only in a certain range)
    3. Write 3 examples of calling the method
    4. Write the method body
    
    Using this recipe for problems 1 and 2 is optional, but highly encouraged.

## Submission
- Your submission will entirely be in the file ```DesignRecipeExamples.java``` which you will upload to Gradescope for the PA1 assignment.
- You should see your grade for the autograded portion of the assignment after submission. If you see an error message instead, you can make a private post to the instructors on Piazza.

*(Several of these examples are borrowed from [How to Design Programs](http://www.htdp.org/2003-09-26/Book/curriculum-Z-H-6.html#node_sec_3.3), and its [Supplemental Material](http://www.htdp.org/2003-09-26/Problems/2.html))*

## Problem 1: Perimeter (1.5 Points, Autograded)
Develop a method named ```perimeter``` that when given the width and height of a rectangle will return its perimeter. 

## Problem 2: Border Area (1.5 Points, Autograded)
Develop a method named ```borderArea``` that given a width and height describing a rectangle, and another width and height describing a rectangle cut out of the center of the other, returns the area of the region between them. For example, the blue area in this shape:

<img width="270" alt="Q2_example" src="https://user-images.githubusercontent.com/25071081/112794129-4620bf00-901b-11eb-98a9-58b31327f6e2.png">

## Problem 3: Converter (3 Points, Open-ended)
### Implementation
Develop a method (with a name of your choice!) that takes one int parameter, converts it to another int value, and returns the new int value. For example, your function could convert:
- Fahrenheit to Celcius
- between currencies

Write a comment for your method, describing what it does and what parameter it takes. If you use any outside sources for the conversion, be sure to cite those in the comment as well.

### Testing
Call your method on at least 3 different examples. Compare each result against a reference converter (Many search engines have built-in converters, or you can use a calculator) and add a comment above the function call to discuss differences (if any) that you get between your program and the reference.

## Problem 4: Combiner (3 Points, Open-ended)
### Implementation
Develop a method (with a name of your choice!) that takes at least two int parameters, combines them to another int value, and returns the new int value. For example, your function could combine:
- Feet and inches into total in inches
- Starting hour and minute and end hour and minute into total number of minutes

Write a comment for your method, describing what it does and what parameters it takes. If you use any outside sources, be sure to cite those in the comment as well.

### Testing
Call your method on at least 3 different examples. Can you call your method with arguments that run, but produce an incorrect output? Call your method with at least one such pair of arguments, and add a comment above it explaining why the output is incorrect. If you cannot find such a pair of arguments, write a comment explaining why you believe no such input exists.
