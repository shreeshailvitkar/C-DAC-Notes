# Core Python 
## Day-1 Introduction
- Python was founded by  Guido van Rossum in 1989 at National Research institute Netherland
- and it release to public in 20 February 1991 
- python is general purpose highlevel programming language
- Dynamically typed language
- Name is came from TV serial on BBC (British Broadcasting Company) 1969-1974 - TV show called Monty Python Flying Circus
- TWO DIFFERENT VERSION HAS DIFFERENT STORY

### Features
- Easy to Code
- Open Source and Free
- Support for GUI
- Object-Oriented Approach
- High-Level Language
- Integrated by Nature
	- Excute code line by line easy to compile
- Highly Portable
- Highly Dynamic 
	- No need to declear as int 
- Integrated Language
- Large Standred library
	- BINOD

### Features from other languages 
- Functional Programming from C
- OOP from C++
- Scripting from Shell and perl
-  Most of syntax is borrowed from c and ABC

### Use of python
1. Desktop App
2. Web Application 
3. Database Applications
4. Network Applications 
5. Data Science 
6. AI, IOT

### Companies using python 
- reddit 
- Google 
- IBM 
- Dropbox 
- Nasa

## Day - 2

### Operations on IDLE 
- +,-,*,/ Do operations in IDLE 
- 10 // 3
- 10 % 3


### Playing with String and print()
-  If you want to type in single ' ' in python outer quote shoud be in " " viceverse
- eg:-
'''python

	print('Here is my "Laptop"')
	print("Here is my 'Laptop'")	

''' 
- To escape the special meaning of any quote you can use \
- To use internal query as it is you can use `print(r'Here is my 'laptop'')`
- You can use number with string to `'facebook' * 10` It will print facebook 10 times 
- \n

### Variables
- Variable is putting values in Container 
- Syntax `name = value`
- Add variable and integer you can do this a=5 `a+5` then it will give 10
- Variable means the value which can be changed
- You can take previous output referance by _ 
- You can Store String into a variable 
- String can be a concatenate 
- String Store in Array  
- Facebook 
- 01234567
- Fetch a <== name[1]
- fetch book <== name[4:8]
- String has indexing starting from 0 
- changing the f to a name[a] = 'a'(not possible)
- String are immutable that means we cannot change the string once it is decleared
- len() function give you length of the String

### Keywords in Python
- 33 keywords
- import keyword <== keyword.kwlist
  
| Keyword | Description |
| --- | ---  | 
| and | a logical operator |
| as | To create an alias |
| assert | For debugging |
| break | To break out of a loop |
| class | To define a class |
| continue | To continue to the next iteration of a loop |
| def |	To define a function |
| del |	To delete an object |
| elif | Used in conditional statements, same as else if |
| else | Used in conditional statements |
| except | Used with exceptions, what to do when an exception occurs |
| False	| Boolean value, result of comparison operations |
| finally | Used with exceptions, a block of code that will be executed no matter if there is an exception or not |
| for	| To create a for loop |
| from	| To import specific parts of a module |
| global | To declare a global variable |
| if	| To make a conditional statement |
| import | To import a module |
| in	| To check if a value is present in a list, tuple, etc. |
| is	| To test if two variables are equal |
| lambda | To create an anonymous function |
| None | Represents a null value |
| nonlocal | To declare a non-local variable |
| not |	A logical operator |
| or |	A logical operator |
| pass | A null statement, a statement that will do nothing |
| raise | To raise an exception |
| return | To exit a function and return a value |
| True | Boolean value, result of comparison operations |
| try |	To make a try...except statement |
| while | To create a while loop |
| with	| Used to simplify exception handling |
| yield	| To end a function, returns a generator |

### List
- list is used to assign multiple values 
- In python list can store different type of variables like int, string
- Operations on list
- mix lists ans = [a,b]
- Functions in List 
- nums.insert(index, value)
- nums.append(value) append at the end 
- append vs insert 
- nums.remove(value)
- nums.pop(index)
- only call pop its using stack 
- remove vs pop
- del nums[2:] delete multiple values
- nums.extends([value, value]) extend existing list
- Inbuild Function on List
	- min(list)
	- max(list)
	- sum(list)
	- list.sort()