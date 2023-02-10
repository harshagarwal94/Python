# Python
Provides Information regarding Python at Vellore institute of Technology (VIT BHOPAL UNIVERSITY) (VIT)

### Course Instructor-  Dr. Priyanka Singh 

# Overview 
(1)


A Brief History of Python, Different Versions, Python 2 vs
Python 3, Installing Python, Environment Variables, Executing
Python from the Command Line, Editing Python Files, Basic
Python Syntax, String Values, String Operators, Numeric Data
Types Conversions, Simple Input and Output, Language
components - Control Flow structures and Syntax - Relational
Operators - Logical Operators - Bit Wise Operators, Python for
Windows


(2)


Conditions, boolean logic, logical operators, ranges, Control
statements: if-else, loops (for, while), Flow control, Functions,
Scoping, Exceptions, Input and output, Modules, Collections,
Lists, Tuples, Sets, Dictionaries, Modules, Standard Modules,
Regular Expressions, Quantifiers, Basic String Operations


(3)


Principles of Object Orientation, Classes in Python, Creating
Classes, Instance Methods, Access Specification, data modeling,
persistent storage of objects, inheritance, polymorphism, operator
overloading, abstract classes, exception handling, try block


(4)


File Handling, Writing Data to a File, Reading Data From a File -
Additional File Methods: Using Pipes as Data Streams, 
HandlingIO Exceptions, Working with Directories, Metadata, File
Organization, Database Programming - Generic Database
Connectivity using ODBC, Postgres connection in Python,
MySQL connection in Python.


(5)


Graphical user interfaces, event-driven programming paradigm,
tkinter module, creating simple GUI, buttons, labels, entry fields,
dialogs, widget attributes - sizes, fonts, colors layouts, nested
frames, Multithreading, Networks, and Client/Server
Programming, introduction to HTML, interacting with remote
HTML server, running html-based queries, downloading pages;
CGI programming, programming a simple CGI form.



### Solution for two inverted and connected flag

```

n=int(input("enter number upto which you want to display "))
for i in range(0,n): #outer loop for number of rows
x=65
for j in range(1,n): #print chr value to n elements
print(chr(x),end=" ")
x=x+1
for l in range(1,2*i-1):# generates 2i-1 spacing
print(" ", end=" ")
if (i == 0):
for k in range(1,n-1):
print(chr(x-2),end=" ")#for 1st row only, decrement the chr value by two as x was incremented in earlier step
x=x-1
else:
print(" ", end=" ") #one spacing extra every time as it is 2i-1 (i is starting from 0)
for m in range(1, n):
print(chr(x-1),end=" ")
x=x-1
n=n-1
print(" ")
```
### Code for Pascal triangle
```
n=7
for j in range(1, n+1) :
for k in range (n,j,-1):
print(" ", end=" ")
a=1
for i in range(1, j+1) :
print(a, end=" ")
a=int(a*(j-i)/i)
print ("\r")
```
# Disclaimer 
* For Educational Purpose
* The repository is made under open Source Licensing for helping the community 
