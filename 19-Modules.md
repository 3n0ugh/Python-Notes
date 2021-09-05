-> Prepared Modules
	=> Standart Librariy Modules
		◇ Written from Python Developers.
	=> Third Person Moduls
	
-> Importing Modules:
	=> We can import modules with import command
		>>> import module_name
	=> We can use dir function to show module's functions and methods.
		>>> dir(module_name)
	=> We can use the attributes like:
		>>> module_name.attribute_or_function
	
-> Different Ways to Importing Modules
	=> Sometimes you need to call modules with another name or you can think it's better than using with module name. Exactly, this times we using this way:
		>>> import module_name as different_name
	=> Also we can import just the attributes from module.
		>>> from module_name import name1, name2, name3, ...
		=> After we importing like that, to call the attribute/function just using their names.
			>>> from os import name
			>>> name
			output: 'posix'
	=> In another way, we are importing and change names of attributes/functions.
		>>> from module_name import name as different_name
	=> The last way to importing modules:
		>>> from module_name import *
		=> It is importing all function and attributes except the starts with '__'.
		=> Also we can use functions/attributes without adding module name.
		=> While we are importing functions/attributes like that, we can't use them in local.
			>>> def function():
							from os import*    // we got an error message.

-> Defining Modules
	=> We can see all modules with os.__file__. (except writing with C.)
	=> Modules are also a programming files. While we are defining a module, Just creating a programming file.
	=> While we are importing our defining module, go the directory is our creating programming file and open a exculisive shell here then use import command.
	
-> Path of Modules (:>)
	=> If we want to import our modules from any directory, we can add the directory to sys.path or copy/move to the directory which including in sys.path.
	
-> Module's Attributes
	=> __import__ : We can importing modules with that command in loops or programms. And we can't use that modules after it works finished. Also we can't use another attributes and functions. If we want to use them, we need to match with a variable like 
		>>> os = __import_('os')
		>>> for module in modules:
		>>> 		__import__(module)
	=> __doc__ :  We can acces documentation string of module with this attribute.
	=> __name__ : While a module is importing __name__ attribute become __main__. So we can use that attribute to control our module. Our module can't start directly and we can access it's attributes.
		>>> if __name__ == '__main__':
		>>> 		some works...
	=> __loader__ : It is giving some info about module importing.
	=> __spec__ : It is giving some info about module.
	=> __package__ :--------------------------------