# OOP Concept
OOP is an acronym for Object Oriented Programming
Basically, OOP is a programming paradigm that represent data in form of REAL-WORLD Object.

Consider a CAR as REAL-WORLD Object.
A car have features like:
- Colour
- Number of wheels
- Number of seats
- Weight
- ... etc

A car also does routines like:
- Starting and stopping the engine
- Steering right or left
- Beeping

In OOP, we define the aforementioned:
- Features as FIELDS
- Routines as METHODS or FUNCTIONS

As such, it's safe to say that CAR is a CLASS of OBJECTS that has the aforementioned features and does the aforementioned routines.


# Java
Java is an OOP language that allows us to represent our data in form of REAL-WORLD objects.

# Classes
The container of any object that we want to represent.

# Fields
Our object's traits and features like: weight, colour, name, age ... etc.

# Methods or Functions
The routines our object does like: sleeping, waking up, singing ... etc.

# Java Syntax
A java class has this syntax
```java
class Class_Name
{
  
}
```
A car class would be represented like this:
```java
class Car
{
  
}
```

A java method has this syntax
```java
type-of-returned-data method_name(arguments)
{
 return some-data; 
}
```

A car method that converts speed from M/H to KM/H would be represented like this:
```java
class Car
{
  int m_to_km(int speed)
  {
    return (speed / 1000);
  }
}
```
int: is the data type that represents numerical values
int speed: is an argument to the method, an argument's definition consists of argument type followed by its name like:
int speed, char a

