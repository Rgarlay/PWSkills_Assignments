



**1Q:- Explain the key features of Python that make it a popular choice for programming.**

Ans:- 
* Python is easy to learn. 
* Python is easy to interpret syntax.

* Python has a large number/collection of , specific for each task.

* Python is already a prominent language in the industry, making it attractive for beginners.

**2Q:- Describe the role of predefined keywords
 in Python and provide examples of
how they are used in a program.**

Ans:- Predefined keywords are commands/functions that are inbuilt and cater to pre-specified 
task.   
They are already equipped with their task/meaning within the syntax and not alterable.      
Their structure forms baseline for syntax of the language.
For example, print() is pre-defined to show the specified output and ‘OR’ is a logical operator defined to compare and output TRUE or FALSE.

  The understanding of the predefined keywords and their syntax 
  allows us to write correct program and interact with the CPU.
Consider the following example:-
```
x = 10
if x > 5: 
print("x is greater than 5") 
elif x == 5: 
print("x is equal to 5") 
else: 
print("x is less than 5")
```
we see that we use if-else statement to print conditional statements.
It leverages predefined meaning of if-else syntax to execute it.

**3Q:- Compare and contrast mutable and immutable objects in Python with examples.**

Ans:- Mutable Objects are those objects which can be changed after they are created. Changes to the object do not result in a new object being created.
For example, Set, Dictionary, List.
```
A = [1,2,3,’Ravi’]
A[-1] = 4
```
This operation will alter ‘Ravi’ to int 4.

IMMUTABLE OBJECTS cannot be altered once they are created. 
String, Tuple, Int variables are few example of such objects.
```
A = ‘Robin’
A[2] = ‘a’
```
This will give an error since it is immutable.

**4Q:- Discuss the different types of operators in Python and provide examples of how they are used.**  

Ans:- Pythons have various types of operators. Following is a list of few of them along with their operation.
1.	Arithmetic Operators:- ‘+’,’-’,’/’,’%’ etc. are known as Arithmetic operators. 
They assist us in doing basic arithmetic calculations such as addition, subtraction, multiplication etc.
Eg: 
```
		Print(f‘The square of {2} is {2**}’)
```
Output:- The square of 2 is 4 

2.	Relational (Comparison) Operators: ==, !=, >, <, >=, <= are known as relational or comparison operators.
They help in comparing two values and return a Boolean result (True or False).
Eg:
```
x, y = 5, 10
print(f'Is {x} greater than {y}? {x > y}')
```
Output:- Is 5 greater than 10? False

3.	Logical Operators: AND, OR, NOT etc. are known as logical operators.
They allow combining multiple conditions or negating a condition for decision-making.
Eg:
```
a, b = 4, 8 
print(f'Is {a} less than {b} and {b} greater than 10? {(a < b) and (b > 10)}')
```
	Output:- Is 4 less than 8 and 8 greater than 10? False
4.	Bitwise Operators: &, |, ^, ~, <<, >> are known as bitwise operators. They operate on integers at the binary level, performing bit-by-bit calculations.
Eg:
```
x, y = 5, 3 
print(f'Bitwise AND of {x} and {y} is {x & y}')
```
Output:- Bitwise AND of 5 and 3 is 1

5.	Assignment Operators: =, +=, -=, *=, /=, %= are examples of assignment operators.
They are used to assign or update values to variables.
Eg:
``` 
x = 10  
x += 5  
print(f'Updated value of x is {x}')  
```
	Output: Updated value of x is 15

6.	Identity Operators: is, is not are known as identity operators.
They check whether two variables refer to the same object in memory.
Eg:
``` 
a, b = [1, 2], [1, 2]
print(f'Are a and b the same object? {a is b}')
```
	Output: Are a and b the same object? False

**5Q:- Explain the concept of type casting in Python with examples.**
Ans:- Concept of Type Casting in Python
Type casting in Python refers to converting a variable from one data type to another. This is helpful when working with mixed data types or when a specific type is required for an operation. For example, if we have a string ‘2’ then we cannot use this directly in a arithmetic operation. For that, we will need to cast it into an int type variable.
Before casting it, it will a string object
```
A = ‘2’
type(A) 
```
After casting it, it will be an int object.
```
Int(A) 
```
**6Q:- How do conditional statements work in Python? Illustrate with examples.**
Ans:- Conditional statements in Python are used to execute certain blocks of code based on specific conditions. If-else,if-elif-else statement are example of  conditional statements. 
Take the example of if-else statement:
```
x = 7 
if x > 10: 
print("x is greater than 10") 
elif x > 5: 
print("x is greater than 5 but less than or equal to 10")
else:
 print("x is 5 or less")
```
Here, we have defined x = 7. 
Our conditional statement will take x value and subject it to the conditions given in the if, elif, else block order-wise and print the respective output if the right condition is met.
Output: x is greater than 5 but less than or equal to 10

**7Q: Describe the different types of loops in Python and their use cases with examples.**  
Ans:- We have 2 loops in python: 
For loop, While loop.
In ‘For loop’ we specify the initialization,steps and end point at the beginning of the block.

Eg:- 
```
	for I in rage(10):
		print(i)
	i = i+1	
```
The while loop repeatedly executes a block of code as long as a given condition evaluates to True. We specify our end condition and then let the block of loop run till the condtion specified is met.
	Eg:- 
```
		X = 0
	While X<= 5:
		Print(X)
		X += 1
```
		


