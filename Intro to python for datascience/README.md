# Introduction To python For Datascience

# Excercise 1:

1) Experiment in the IPython Shell; type 5 / 8, for example.
2) Add another line of code to the Python script: print(7 + 10).
3) Hit Submit Answer to execute the Python script and receive feedback.

Solution
````
# Example, do not modify!
print(5 / 8)

# Put code below here
print(7+10)

````

# Excercise 2:

When to use Python?
Python is a pretty versatile language. For which applications can you use Python?

a) You want to do some quick calculations.
b) For your new business, you want to develop a database-driven website.
c) Your boss asks you to clean and analyze the results of the latest satisfaction survey.
d) All of the above.

Solution : d(All of the above.)

# Excercise 3:

Any comments?
Something that Filip didn't mention in his videos is that you can add comments to your Python scripts. Comments are important to make sure that you and others can understand what your code is about.

To add comments to your Python script, you can use the # tag. These comments are not run as Python code, so they will not influence your result. As an example, take the comment on the right, # Division; it is completely ignored during execution.

Solution : 
````
# Division
print(5 / 8)

# Addition
print(7 + 10)

````

# Excercise 4:

Python as a calculator
Python is perfectly suited to do basic calculations. Apart from addition, subtraction, multiplication and division, there is also support for more advanced operations such as:

Exponentiation: **. This operator raises the number to its left to the power of the number to its right. For example 4**2 will give 16.
Modulo: %. This operator returns the remainder of the division of the number to the left by the number on its right. For example 18 % 7 equals 4.
The code in the script on the right gives some examples.
Instructions : 
Suppose you have $100, which you can invest with a 10% return each year. After one year, it's 100×1.1=110 dollars, and after two years it's 100×1.1×1.1=121. Add code on the right to calculate how much money you end up with after 7 years.

Solution : 
````
# Addition, subtraction
print(5 + 5)
print(5 - 5)

# Multiplication, division, modulo, and exponentiation
print(3 * 5)
print(10 / 2)
print(18 % 7)
print(4 ** 2)

# How much is your $100 worth after 7 years?
print(100*1.1**7)

````
# Excercise 5:

Create a variable savings with the value 100.
Check out this variable by typing print(savings) in the script.

Solution : 
````
# Create a variable savings
savings = 100

# Print out savings
print(savings)
````

# Excercise 6:

Create a variable growth_multiplier, equal to 1.1.
Create a variable, result, equal to the amount of money you saved after 7 years.
Print out the value of result.

Solution : 
````
# Create a variable savings
savings = 100

# Create a variable growth_multiplier
growth_multiplier = 1.1

# Calculate result
result = (100 * 1.1 ** 7)

# Print out result
print(result)
````

# Excercise 7:

Create a new string, desc, with the value "compound interest".
Create a new boolean, profitable, with the value True.

Solution : 
````
# Create a variable desc
desc = "compound interest"

# Create a variable profitable
profitable = True
````

# Excercise 8:

To find out the type of a value or a variable that refers to that value, you can use the type() function. Suppose you've defined a variable a, but you forgot the type of this variable. To determine the type of a, simply execute:

type(a)
We already went ahead and created three variables: a, b and c. You can use the IPython shell on the right to discover their type. Which of the following options is correct?

Possible Answers : 

a) a is of type int, b is of type str, c is of type bool
b) a is of type float, b is of type bool, c is of type str
c) a is of type float, b is of type str, c is of type bool
d) a is of type int, b is of type bool, c is of type str

Solution :  c(a is of type float, b is of type str, c is of type bool)

# Excercise 9:

Calculate the product of savings and growth_multiplier. Store the result in year1.
What do you think the resulting type will be? Find out by printing out the type of year1.
Calculate the sum of desc and desc and store the result in a new variable doubledesc.
Print out doubledesc. Did you expect this?

Solution : 

````
savings = 100
growth_multiplier = 1.1
desc = "compound interest"

# Assign product of growth_multiplier and savings to year1
year1 = savings * growth_multiplier

# Print the type of year1
print(type(year1))

# Assign sum of desc and desc to doubledesc
doubledesc = desc + desc

# Print out doubledesc
print(doubledesc)
````

# Excercise 10:

Hit Run Code to run the code on the right. Try to understand the error message.
Fix the code on the right such that the printout runs without errors; use the function str() to convert the variables to strings.
Convert the variable pi_string to a float and store this float as a new variable, pi_float.

Solution : 

````
# Definition of savings and result
savings = 100
result = 100 * 1.10 ** 7

# Fix the printout
print("I started with $" + str(savings) + " and now have $" + str(result) + ". Awesome!")

# Definition of pi_string
pi_string = "3.1415926"

# Convert pi_string into float: pi_float
pi_float = float(pi_string)

````

# Excercise 11:

Can Python handle everything?
Now that you know something more about combining different sources of information, have a look at the four Python expressions below. Which one of these will throw an error? You can always copy and paste this code in the IPython Shell to find out!

Options : 

a) "I can add integers, like " + str(5) + " to strings."
b) "I said " + ("Hey " * 2) + "Hey!"
c) "The correct answer to this multiple choice exercise is answer number " + 2
d) True + False

Solution : c("The correct answer to this multiple choice exercise is answer number " + 2)

# Excercise 12:

Create a list, areas, that contains the area of the hallway (hall), kitchen (kit), living room (liv), bedroom (bed) and bathroom (bath), in this order. Use the predefined variables.
Print areas with the print() function.

Solution : 

````
# area variables (in square meters)
hall = 11.25
kit = 18.0
liv = 20.0
bed = 10.75
bath = 9.50

# Create list areas

areas = [hall, kit, liv, bed, bath]
# Print areas
print(areas)
````
# Excercise 13:

Finish the line of code that creates the areas list. Build the list so that the list first contains the name of each room as a string and then its area. In other words, add the strings "hallway", "kitchen" and "bedroom" at the appropriate locations.
Print areas again; is the printout more informative this time?

Solution : 

````
# area variables (in square meters)
hall = 11.25
kit = 18.0
liv = 20.0
bed = 10.75
bath = 9.50

# Adapt list areas
areas = ["hallway", hall, "kitchen", kit, "living room", liv, "bedroom", bed, "bathroom", bath]

# Print areas
print(areas)
````
# Excercise 14:

Select the valid list
A list can contain any Python type. But a list itself is also a Python type. That means that a list can also contain a list! Python is getting funkier by the minute, but fear not, just remember the list syntax:

my_list = [el1, el2, el3]
Can you tell which ones of the following lines of Python code are valid ways to build a list?

A. [1, 3, 4, 2] B. [[1, 2, 3], [4, 5, 7]] C. [1 + 2, "a" * 5, 3]

Options : 


a) A, B and C
b) B
c) B and C
d) C

Solution : a(A, B and C)

# Excercise 15:

Finish the list of lists so that it also contains the bedroom and bathroom data. Make sure you enter these in order!
Print out house; does this way of structuring your data make more sense?
Print out the type of house. Are you still dealing with a list?

Solution : 

````
# area variables (in square meters)
hall = 11.25
kit = 18.0
liv = 20.0
bed = 10.75
bath = 9.50

# house information as list of lists
house = [["hallway", hall],
         ["kitchen", kit],
         ["living room", liv],
         ["bedroom", bed],
         ["bathroom", bath]]

# Print out house
print(house)

# Print out the type of house
print(type(house))
````

# Excercise 16:

Print out the second element from the areas list (it has the value 11.25).
Subset and print out the last element of areas, being 9.50. Using a negative index makes sense here!
Select the number representing the area of the living room (20.0) and print it out.

Solution:

````
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Print out second element from areas
print(areas[1])

# Print out last element from areas
print(areas[-1])

# Print out the area of the living room
print(areas[-5])
````

# Excercise 17:

Using a combination of list subsetting and variable assignment, create a new variable, eat_sleep_area, that contains the sum of the area of the kitchen and the area of the bedroom.
Print the new variable eat_sleep_area.

Solution:

````
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Sum of kitchen and bedroom area: eat_sleep_area
eat_sleep_area = areas[3] + areas[-3]

# Print the variable eat_sleep_area
print(eat_sleep_area)
````

# Excercise 18:

Use slicing to create a list, downstairs, that contains the first 6 elements of areas.
Do a similar thing to create a new variable, upstairs, that contains the last 4 elements of areas.
Print both downstairs and upstairs using print().

Solution:

````
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Use slicing to create downstairs
downstairs = areas[0:6]

# Use slicing to create upstairs
upstairs = areas[6:10]

# Print out downstairs and upstairs
print(downstairs)
print(upstairs)
````

# Excercise 19:

Create downstairs again, as the first 6 elements of areas. This time, simplify the slicing by omitting the begin index.
Create upstairs again, as the last 4 elements of areas. This time, simplify the slicing by omitting the end index.

Solution:

````
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Alternative slicing to create downstairs
downstairs = areas[:6]

# Alternative slicing to create upstairs
upstairs = areas[6:]
````

# Excercise 20:

Subsetting lists of lists
You saw before that a Python list can contain practically anything; even other lists! To subset lists of lists, you can use the same technique as before: square brackets. Try out the commands in the following code sample in the IPython Shell:

x = [["a", "b", "c"],
     ["d", "e", "f"],
     ["g", "h", "i"]]
x[2][0]
x[2][:2]
x[2] results in a list, that you can subset again by adding additional square brackets.

What will house[-1][1] return? house, the list of lists that you created before, is already defined for you in the workspace. You can experiment with it in the IPython Shell.

Options:


a) A float: the kitchen area
b) A string: "kitchen"
c) A float: the bathroom area
d) A string: "bathroom"

Solution : c(A float: the bathroom area)


# Excercise 21:

Update the area of the bathroom area to be 10.50 square meters instead of 9.50.
Make the areas list more trendy! Change "living room" to "chill zone".

Solution:

````
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Correct the bathroom area
areas[-1] = 10.50

# Change "living room" to "chill zone"
areas[4] = 'chill zone'

````

# Excercise 22:

Use the + operator to paste the list ["poolhouse", 24.5] to the end of the areas list. Store the resulting list as areas_1.
Further extend areas_1 by adding data on your garage. Add the string "garage" and float 15.45. Name the resulting list areas_2.

Solution : 

````
# Create the areas list and make some changes
areas = ["hallway", 11.25, "kitchen", 18.0, "chill zone", 20.0,
         "bedroom", 10.75, "bathroom", 10.50]

# Add poolhouse data to areas, new list is areas_1
areas_1 = areas + ["poolhouse", 24.5]

# Add garage data to areas_1, new list is areas_2
areas_2 = areas_1 + ["garage", 15.45]
````
# Excercise 23:

Delete list elements
Finally, you can also remove elements from your list. You can do this with the del statement:

x = ["a", "b", "c", "d"]
del(x[1])
Pay attention here: as soon as you remove an element from a list, the indexes of the elements that come after the deleted element all change!

The updated and extended version of areas that you've built in the previous exercises is coded below. You can copy and paste this into the IPython Shell to play around with the result.

areas = ["hallway", 11.25, "kitchen", 18.0,
        "chill zone", 20.0, "bedroom", 10.75,
         "bathroom", 10.50, "poolhouse", 24.5,
         "garage", 15.45]
There was a mistake! The amount you won with the lottery is not that big after all and it looks like the poolhouse isn't going to happen. You decide to remove the corresponding string and float from the areas list.

The ; sign is used to place commands on the same line. The following two code chunks are equivalent:

Same line
command1; command2

Separate lines
command1
command2
Which of the code chunks will do the job for us?

Options :

a) del(areas[10]); del(areas[11])
b) del(areas[10:11])
c) del(areas[-4:-2])
d) del(areas[-3]); del(areas[-4])

Solution : c(del(areas[-4:-2]))

# Excercise 24:

Change the second command, that creates the variable areas_copy, such that areas_copy is an explicit copy of areas. After your edit, changes made to areas_copy shouldn't affect areas. Hit Submit Answer to check this.

Solution : 

````
# Create list areas
areas = [11.25, 18.0, 20.0, 10.75, 9.50]

# Create areas_copy
areas_copy = areas[:]

# Change areas_copy
areas_copy[0] = 5.0

# Print areas
print(areas)
````

# Excercise 25:

Use print() in combination with type() to print out the type of var1.
Use len() to get the length of the list var1. Wrap it in a print() call to directly print it out.
Use int() to convert var2 to an integer. Store the output as out2.

Solution:

````
# Create variables var1 and var2
var1 = [1, 2, 3, 4]
var2 = True

# Print out type of var1
print(type(var1))

# Print out length of var1
print(len(var1))

# Convert var2 to an integer: out2
out2 = int(var2)
````

# Excercise 26:

Help!
Maybe you already know the name of a Python function, but you still have to figure out how to use it. Ironically, you have to ask for information about a function with another function: help(). In IPython specifically, you can also use ? before the function name.

To get help on the max() function, for example, you can use one of these calls:

help(max)
?max
Use the Shell on the right to open up the documentation on complex(). Which of the following statements is true?

Options : 

a) complex() takes exactly two arguments: real and [, imag].
b) complex() takes two arguments: real and imag. Both these arguments are required.
c) complex() takes two arguments: real and imag. real is a required argument, imag is an optional argument.
d) complex() takes two arguments: real and imag. If you don't specify imag, it is set to 1 by Python.

Solution : c(complex() takes two arguments: real and imag. real is a required argument, imag is an optional argument.)
