In Python, a class is a custom data type that acts as a blueprint for creating things. 
While built-in types like integers or strings are great for simple data, 
classes let you define your own complex structures that group related data and behaviors together. 
An object (often called an instance) is a specific, concrete example created from that class blueprint. 
For instance, if Car is the class blueprint, a specific red Toyota occupying space in your computer's memory would be the object instance.

To set up an object the moment it is created, Python classes should use a special constructor method named __init__. This method runs automatically when you instantiate a new object, and its primary job is to initialize the object's starting state or attributes. By defining an __init__ constructor, you ensure that every new object starts its life fully formed and ready to be used, populated with its own unique starting data.

Beyond storing data, classes can perform actions using methods, which are simply functions defined directly inside the class block. To command an object to execute one of its methods, or to access its internal data, you use the dot (.) operator. For example, typing my_car.drive() uses the dot operator to tell that specific Car object to trigger its drive behavior.

Behind the scenes, when you use dot notation, Python automatically passes the object itself into the method as the very first argument. In Python, this first parameter must be explicitly written in your method definitions and is universally named self. The self parameter acts as a direct link back to the object, which is how the method knows which specific object's data it should be looking at or modifying.

