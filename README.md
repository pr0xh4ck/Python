# Python
> All about python for Hacker & Developer 
```
If you think python is not easy and it's very difficult to learn, that's why I make this content for you guys.
```
---

## Agenda 

 - [Basic](#basic)
   - [Variables](#variables)
   - [Data types](#data-types)
   - [Data types example](#example)
 - [Hacker](#hacker)
 - [Developer](#developer)
 
 ---
 
 
 
 ### basic 
 
 - Q 1: What is Python ?

```
- Dynamic, Interpreted, Object-Oriented and high-level programing language. 
- Enables cross-platform rapid prototyping and scripting.
- Relatively simple, easy to learn syntax.
- General purpose and versatile with a mature standard library.
- Extensible, actively used with a large community.

```
 
- Q 2: Why learn Pyton as a hacker ?

```
- Understand how scripts of proof of concepts work.
- Debug, modify and run scripts or proof of concepts.
- Create your own script of proof of concepts.
- Easy & first programing language of beginners.
- Understanding how an application could work makes it easier to anticipate how it could break.

```
 
 - Q 3: Python2 vs Python3

```
- Python2 is no longer under development but people still use it
- Python2 code will(mostly) not run in a Python3 environment
- Python3 stores strings as unicode by default(not ASCII)
- If you don't know to run a script, try both or try to print
- If you have a choice - use Python3(Python2 is end of life)
```
 
 
 
 
 ### variables
 ```
Python has no command for declaring a variable.
> A variable is created the moment you first assign a value to it.

ex:
x = 1
y = 12

> If you want to specify the data type of a variable.
ex:
x = str(3)    # x will be '3'
y = int(3)    # y will be 3
z = float(3)  # z will be 3.0

> You can get the data type of a variable with the type() function.
ex:
x = 5
y = "John"
print(type(x))
print(type(y))

> String variables can be declared either by using single or double quotes:
ex:
x = "John"
# is the same as
x = 'John'

> Variable names are case-sensitive.
ex:
a = 4
A = "Sally"
#A will not overwrite a

> Legal variable names:
ex:
myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"

> Illegal variable names:
ex:
2myvar = "John"
my-var = "John"
my var = "John"

> Python allows you to assign values to multiple variables in one line:
ex:
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)

> And you can assign the same value to multiple variables in one line:
ex:
x = y = z = "Orange"
print(x)
print(y)
print(z)

> If you have a collection of values in a list, tuple etc. Python allows you extract the values into variables. This is called unpacking.
ex:
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)

> The Python print statement is often used to output variables.To combine both text and a variable, Python uses the + character:
ex:
x = "awesome"
print("Python is " + x)

> You can also use the + character to add a variable to another variable:
ex:
x = "Python is "
y = "awesome"
z =  x + y
print(z)

> For numbers, the + character works as a mathematical operator:
ex:
x = 5
y = 10
print(x + y)

> If you try to combine a string and a number, Python will give you an error:
ex:
x = 5
y = "John"
print(x + y)

> Create a variable outside of a function, and use it inside the function.
ex:
x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc()

> Create a variable inside a function, with the same name as the global variable.
ex:
x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()

print("Python is " + x)

> If you use the global keyword, the variable belongs to the global scope:
ex:
def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)

> To change the value of a global variable inside a function, refer to the variable by using the global keyword:
ex:
x = "awesome"

def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)

```
 
 
 
 
 
 
 
 
 
 
 ### data-types
```
Text Type:	str
Numeric Types:	int, float, complex
Sequence Types:	list, tuple, range
Mapping Type:	dict
Set Types:	set, frozenset
Boolean Type:	bool
Binary Types:	bytes, bytearray, memoryview
```
### example
```
x = "Hello World"	str	
x = 20	int	
x = 20.5	float	
x = 1j	complex	
x = ["apple", "banana", "cherry"]	list	
x = ("apple", "banana", "cherry")	tuple	
x = range(6)	range	
x = {"name" : "John", "age" : 36}	dict	
x = {"apple", "banana", "cherry"}	set	
x = frozenset({"apple", "banana", "cherry"})	frozenset	
x = True	bool	
x = b"Hello"	bytes	
x = bytearray(5)	bytearray	
x = memoryview(bytes(5))	memoryview
``` 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 ### hacker
 
  - 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 ### developer
 















