- Prepared Modules
	- Standart Librariy Modules
		- Written from Python Developers.
	- Third Person Moduls
	
- Importing Modules:
	- We can import modules with import command
		```python
			import module_name
		```
	- We can use the dir function to show the module's functions and methods.
		```python
			dir(module_name)
		```
	- We can use the attributes like:
		```python
			module_name.attribute_or_function
		```
	
- Different Ways to Importing Modules
	- Sometimes, you need to call modules with another name. Or you can think it's better than using the module name. Exactly, this times we used this way:
		```python
			import module_name as different_name
		```
	- Also, we can import just the attributes from the module.
		```python
			from module_name import name1, name2, name3, ...
		```
		- After we importing like that, to call the attribute/function just using their names.
			```python
				from os import name
				name
				# output: 'posix'
			```
	- In another way, we are importing and change the names of attributes/functions.
		```python
			from module_name import name as different_name
		```
	- The last way to importing modules:
		```python
			from module_name import *
		```
		- It is importing all function and attributes except the starts with '__'.
		- Also we can use functions/attributes without adding module name.
		- While we are importing functions/attributes like that, we can't use them in local.
			```python
				def function():
					from os import* # we got an error message.
			```

- Defining Modules
	- We can see all modules with os.\_\_file__. (except writing with C.)
	- Modules are also programming files. While we are defining a module, Just creating a programming file.
	- While we are importing our defining module, go the directory is our creating programming file and open an exclusive shell here then, use the import command.
	
- Path of Modules (:>)
	- If we want to import our modules from any directory, we can add the directory to the sys.path or copy/move to the directory which is contained in the sys.path.
	
- Module's Attributes
	- \_\_import__ : We can importing modules with that command in loops or programms. And we can't use that modules after it works finished. Also we can't use another attributes and functions. If we want to use them, we need to match with a variable like 
		```python
			os = __import_('os')
			for module in modules:
				__import__(module)
		```
	- \_\_doc__ :  We can acces documentation string of module with this attribute.
	- \_\_name__ : While a module is importing \_\_name__ attribute become \_\_main__. So we can use that attribute to control our module. Our module can't start directly and we can access it's attributes.
		```python
			if __name__ == '__main__':
				some works...
		```
	- \_\_loader__ : It is giving some info about module importing.
	- \_\_spec__ : It is giving some info about module.
	- \_\_package__ :--------------------------------
