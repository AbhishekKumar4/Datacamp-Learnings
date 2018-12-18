# Introduction To python For Datascience

Excercise :

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

Excercise 2:

When to use Python?
Python is a pretty versatile language. For which applications can you use Python?

a) You want to do some quick calculations.
b) For your new business, you want to develop a database-driven website.
c) Your boss asks you to clean and analyze the results of the latest satisfaction survey.
d) All of the above.

Solution : d(All of the above.)

Excercise 3:

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

Excercise 3:

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
Excercise 4:

Create a variable savings with the value 100.
Check out this variable by typing print(savings) in the script.

Solution : 
````
# Create a variable savings
savings = 100

# Print out savings
print(savings)
````

Excercise 5:

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

Excercise 6:

Create a new string, desc, with the value "compound interest".
Create a new boolean, profitable, with the value True.

Solution : 
````
# Create a variable desc
desc = "compound interest"

# Create a variable profitable
profitable = True
````

Excercise 7:

To find out the type of a value or a variable that refers to that value, you can use the type() function. Suppose you've defined a variable a, but you forgot the type of this variable. To determine the type of a, simply execute:

type(a)
We already went ahead and created three variables: a, b and c. You can use the IPython shell on the right to discover their type. Which of the following options is correct?

Possible Answers : 

a) a is of type int, b is of type str, c is of type bool
b) a is of type float, b is of type bool, c is of type str
c) a is of type float, b is of type str, c is of type bool
d) a is of type int, b is of type bool, c is of type str

Solution :  c(a is of type float, b is of type str, c is of type bool)

Excercise 8:

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

Excercise 9:

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

Excercise 10:

Can Python handle everything?
Now that you know something more about combining different sources of information, have a look at the four Python expressions below. Which one of these will throw an error? You can always copy and paste this code in the IPython Shell to find out!

Options : 

a) "I can add integers, like " + str(5) + " to strings."
b) "I said " + ("Hey " * 2) + "Hey!"
c) "The correct answer to this multiple choice exercise is answer number " + 2
d) True + False

Solution : c("The correct answer to this multiple choice exercise is answer number " + 2)
