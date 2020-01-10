# Lesson Two

## What is a variable?

A variable holds a value.
```python
message = "Hello Python world!"
print(message)
```
You can change the value of a variable at any point.
```python
message = "Hello Python world!"
print(message)

message = "Python is my favorite language!"
print(message)
```
{% next %}

# Naming Rules
Variables can only contain letters, numbers, and underscores. Variable names can start with a letter or an underscore, but can not start with a number.
Spaces are not allowed in variable names, so we use underscores instead of spaces. For example, use student_name instead of "student name".
You cannot use Python keywords as variable names.
Variable names should be descriptive, without being too long. For example mc_wheels is better than just "wheels", and number_of_wheels_on_a_motorycle.
Be careful about using the lowercase letter l and the uppercase letter O in places where they could be confused with the numbers 1 and 0.

NameError
There is one common error when using variables, that you will almost certainly encounter at some point. Take a look at this code, and see if you can figure out why it causes an error.


message = "Thank you for sharing Python with the world, Guido!"
print(mesage)


Let's look through this error message. First, we see it is a NameError. Then we see the file that caused the error, and a green arrow shows us what line in that file caused the error. Then we get some more specific feedback, that "name 'mesage' is not defined".

You may have already spotted the source of the error. We spelled message two different ways. Python does not care whether we use the variable name "message" or "mesage". Python only cares that the spellings of our variable names match every time we use them.

This is pretty important, because it allows us to have a variable "name" with a single name in it, and then another variable "names" with a bunch of names in it.

We can fix NameErrors by making sure all of our variable names are spelled consistently.


message = "Thank you for sharing Python with the world, Guido!"
print(message)


In case you didn't know Guido van Rossum created the Python language over 20 years ago, and he is considered Python's Benevolent Dictator for Life. Guido still signs off on all major changes to the core Python language.

EXERCISES
Hello World - variable
Store your own version of the message "Hello World" in a variable named my_var, and print it.

One Variable, Two Messages:
Store a message in a new variable called new_var, and then print that message.
Store a new message in the same variable, and then print that new message.
