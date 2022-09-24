# DESTRUCTORS-IN-C++

# Destructor is also a special member function like constructor. Destructor destroys the class objects created by constructor. 

# Destructor has the same name as their class name preceded by a tilde (~) symbol.

# It is not possible to define more than one destructor. 

# The destructor is only one way to destroy the object create by constructor. Hence destructor can-not be overloaded.

# Destructor neither requires any argument nor returns any value.

# It is automatically called when object goes out of scope. 

Syntax:

Syntax for defining the destructor within the class
~ <class-name>()
{

}


Syntax for defining the destructor outside the class
<class-name>: : ~ <class-name>()
{

}
