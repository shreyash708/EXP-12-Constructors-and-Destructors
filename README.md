# EXP-12-Constructors-and-Destructors

# Aim: To study and implement Constructors and Destructors

# THERORY:
•	The name of the constructor is same as its class name. 
•	Constructors are mostly declared in the public section of the class though it can be declared in the private section of the class. 
•	Constructors do not return values; hence they do not have a return type. 
•	 A constructor gets called automatically when we create the object of the class. 
•	Constructors are used when variables need to be initiated before object is called.
•	Constructors can be overloaded. 
•	Constructor cannot be declared virtual

# Algorithm:
# Experiment 12A – Constructor Inside the Class
Start the program.
Define a class with private data members (e.g., pages, title, price).
Implement a constructor inside the class that takes input from the user to initialize members.
Create an object of the class.
Display the initialized values using a member function.
End.
# Experiment 12B – Constructor Outside the Class
Start the program.
Declare a constructor inside the class.
Define the constructor outside the class using the scope resolution operator.
Take input in the constructor to initialize data members.
Create an object of the class.
Display the data using a member function.
End.
# Experiment 12C – Parameterized Constructor
Start the program.
Define a class with private data members (e.g., roll, name).
Implement a parameterized constructor that initializes members using arguments.
Create an object by passing values during object creation.
Display the object details using a member function.
End.
# Experiment 12D – Copy Constructor
Start the program.
Define a class with private data members.
Implement a parameterized constructor for initial object creation.
Implement a copy constructor that creates a new object by copying an existing object’s data members.
Create an original object and then a copied object using the copy constructor.
Display both objects’ data to verify.
End.
# Experiment 12E – Destructor
Start the program.
Define a class with a constructor and destructor.
Use global or static counters to track the number of objects created and destroyed.
Display messages inside constructor and destructor to show object lifecycle.
Create multiple objects and nested scopes to demonstrate destructor calls as objects go out of scope.
End.


# CONCLUSION :
Learned how parameterized constructors help create objects with initial values.
Explored copy constructors for copying objects safely.

