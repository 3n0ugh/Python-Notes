=> Instance Attributes:
	->__init__ functiond and self:
		- We need two things to define instance attributes : 
			-) __init__ functions and it's first parameter must be self.
		- If we using them, class didn't give output directly.
		- If we would to take output from class, need to do instantiation.
		- While we are calling the attributes python is looking first instance attributes then - if it isn't in instance attributes- class attributes. (if we have same name two attributes.)
		- If we want to read the class attributes, we will use class name (not using the instance of class.)
	!!!!- If we define an instance attributes, we need to put first 'self' word and don't use 'self' word out of function because the word is gaining mean while using in function.
		- Values of instance attributes are specific
		!!!! - I mean, while we are adding any value in instance attributes, it just change that instance. Another instances are not changing.

=> Instance Methods:
	-> If we define any function with 'self' parameter, it is the instance method.
	
=> Class Methods:
	-> Same mean with instance methods but this time we are using 'cls' parameter. Also we need '@classmethod' decorator.
		- example : 	class x():
									y = []
									@classmethod
									def z(cls):
										return cls.y
										
=>Alternative Constructor:
	-> Just they offer to us alternative ways to solve our problem.
	
=> Static Methods:
	-> We are using '@staticmethod' decorator to define static methods.
	-> We use class-related methods that does not need to be in the class to avoid disrupting class integrity.
	
=> Class Members:
	1-) Public Members
	2-) Private Members
	3-) Semi-Private Members
	-> Public Members:
		- We already learn the public members while coming here. All we learned about class are public members.
	-> Private Members:
		- We can reach private members in class, but we can;t reach them out of class.
		- Any member to become private member, it needs to has two underline at first and max one underline at bottom.
		- example:		__private = ' '
								__private_ = ' '
								__private_unit = ' '		- They are all private members.
								__private_unit_ = ' '	
		- Also we can reach them with name mangling.
			-example:   >>> s = class()
								>>> s._class__private
	-> Semi-Private Members:
		-To indicate any semi-private member we are putting an undeline at first of attributes.
		-It is reachable but we shouldn't change them.(because  the programmer know something :)
=> @property Decorator:
	-The main thing the @propert decorator does is to make a method usable as an attribute.
	-Another @property ability is it can create read only attributes.
	=> @property
	=> @method_name.setter : to add or to verificate
	=> @method_name.deleter : to delete
			- While we are using @propert decorator, we define three different methods.	

=> Inheritance 
	-> Base Classes
		- Base classes are including common attributes and methods of another classes.
			-> Subclass
				-The base class defines common attributes and methods of the subclasses that will derive from it.
		-> 1-) All the qualities and methods of the inherited class are transferred to the subclass as they are.
		-> 2-) Some attributes and methods of the inherited class are redefined in the subclass.
		-> 3-) Some attributes and methods of the inherited class are changed in the subclass.
		-> super() function: It is protecting base class attributes and methods. Also provide to add attribute to subclasses.
	
=>Tkinter
	-> mainloop():
		- We use this function to creating a window on screen.
	-> pack():
		- After the label and button creating, pack() function putting them to window.
	
=> Multiple Inheritance
	-> If we use more than one class as a parameter when inheriting it is called multiple inheritance.
	
=> Composition
	-> Composition is a concept that models a has a relationship. It enables creating complex types by combining objects of other types. This means that a class Composite can contain an object of another class Component . This relationship means that a Composite has a Component .
	
=>	1-) Construction
=>	2-) Initialization					& 3 stage of classes.
=>	3-) Destruction

=> __new__():
	-> This function responsible for construction.
	
	