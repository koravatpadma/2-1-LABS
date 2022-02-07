Write a C++ Program to illustrate concept of Virtual Functions

A virtual function is a member function which is declared within a base class and is re-defined (overridden) by a derived class.

When you refer to a derived class object using a pointer or a reference to the base class, you can call a virtual function for that object

execute the derived class’s version of the function. 

Virtual functions ensure that the correct function is called for an object, regardless of the type of reference (or pointer) used for function call. 

They are mainly used to achieve Runtime polymorphism Functions are declared with a virtual keyword in base class.

The resolving of function call is done at runtime
