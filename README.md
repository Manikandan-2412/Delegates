# Delegates
Learning Something about delegate

intro
-----
delegate is a method which takes a one more method as a parameter

A delegates is a type that holds a reference to a method,
Delegate is also called as function pointers

one function is pointing to the another function

delegate is a method without any logic and this method can point to any other method having similar signature
to point to a method first create a object for delegates 

//syntax
public delegate void hi();
hi obj=new hi(abc); // creating  the objects
obj.invoke(); // invoking the method

Adv : --> this makes application "Logic independent"
Logic independent:
   making a logic dynamically
there are the three steps involved 
delegate declaration
         Instantiation
         Invocation
funk is the inbuilt delegates

Some commonly used features:
------------------------

nullable types
partial 
global using
tuple
-----------------
Nullable Type:
-----------
Nullable datatype represents the value-type varaibles
use the HasValue and Value read-only properties to test for null and retrieve the value
? is used for using nullable
Syntax:
  int? num=null;
  
------------
partial Type:
-----------
is used to reduce the file size and split the files and can be accessible by every file
partial is used for simualtenously we can able to work 

-----------------
Tuple
------
is used for returing multiple values
it is a generic type

---------------------
Global Using
--------------
global:: --> is used for the checking the class for searching without namespace
