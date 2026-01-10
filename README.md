# Learning-
f-strings Practice: 
**Before f-strings (old way):**

name = "Alice"
age = 25
message = "My name is " + name + " and I am " + str(age) + " years old"

**With f-strings (modern way):**

name = "Alice"
age = 25
message = f"My name is {name} and I am {age} years old"

......................................................................
The **input() function** pauses your program and waits for the user to type something and press Enter.

name = input("What's your name? ")
print(f"Hello, {name}!")
NOTE ___: age = int(input("How old are you? "))  # Converts string to integer
......................................................................................
**Truthy & Falsy Values:**
Falsy values:

False
None
0 (zero)
0.0 (zero float)
"" (empty string)
[] (empty list)
{} (empty dictionary)
false in if condition : How if works in Python (core idea)

In Python, an if statement checks the truth value of an expression:
if <expression>:
    # runs only if expression is True
Python internally converts <expression> to a boolean using:
bool(<expression>)
❌ Falsy examples (treated as False)
if 0:
    print("This won't print")
0 is considered False
bool(0) → False
So the block is skipped
