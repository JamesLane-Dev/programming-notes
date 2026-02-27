In Python, a class is a user-defined type that defines both data (attributes) and behavior (methods). It acts as a blueprint for creating objects.

While built-in types like integers or strings are great for simple data, 
classes let you define your own complex structures that group related data and behaviors together. 
An object (often called an instance) is a specific, concrete example created from that class blueprint. 
For instance, if Car is the class blueprint, a specific red Toyota occupying space in your computer's memory would be the object instance.

To set up an object the moment it is created, Python classes should use a special constructor method named __init__. This method runs automatically when you instantiate a new object, and its primary job is to initialize the object's starting state or attributes. The __init__ method initializes the object's internal state by assigning values to its instance attributes.

Beyond storing data, classes can perform actions using methods, which are simply functions defined directly inside the class block. To command an object to execute one of its methods, or to access its internal data, you use the dot (.) operator. When calling my_car.drive(), Python internally translates it to Car.drive(my_car). This is why the method must accept self as its first parameter.

Behind the scenes, when you use dot notation, Python automatically passes the object itself into the method as the very first argument. In Python, this first parameter must be explicitly written in your method definitions and is universally named self. self is not a keyword in Python, but a naming convention. It represents the instance that the method is operating on.

Mental Model:
- A class defines structure and behavior.
- An object stores its own state.
- Methods operate on that state.
- self refers to the current instance.

