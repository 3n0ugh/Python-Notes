- Generators, Another Data Types, Dictionary Generators, Set Generators, Functions all of them are- abs():
   - This function is giving any number's absolute value.
   ```python
      abs(-20)
      # output: 20
   ```
   - Also, it can take just a parameter.

- round():
   - This function rounds up the numbers.
   - Also, if we give a second parameter, we can arrange the sensitivity of round upping.

- all():
   - If all units bool values are true, it gives us true value but, if at least one unit is false, it gives us false value.
   - We can use this function to control bool values of codes.

- any():
   - If at least one unit has true value, this function gives us true value. If it hasn't any true value unit, it gives us a false value.
   - We can use this function to control bool values of codes.

- ascii():
   - It gives us any object format to print screen.
   - Also, it gives a Unicode version of Turkish characters.

- repr():
   - Same work with ascii() but, it gives to use non-ASCII characters with character versions.

- bool():
   - It gives bool value of objects.

- bin():
   - That function gives any numbers equivalent in the binary system.

- bytes():
   - That function converts other data types to byte data types.
   - If you enter a number as a parameter, the function gives us the byte object amount of what we entered.
   - When we want to convert strings to byte data types, we enter an encoding parameter as a second parameter.
      ```python
         bytes('light', 'utf-8')
      ```
      • also we can use like : 
      ```python
         bytes('light', encoding='ascii')
      ```
   - If our entered string does not define by the encoder, we got UnicodeEncodeError error.

- bytearray():
   - Working like bytes() but, byte arrays are mutable data types.

- chr():
   - That function converts the integer to characters.
   - While converting integer, it takes as a base the UNICODE.

- list():
   - It can use for creating a list or converting other data types to a list.

- set():
   - It can use for creating a set or converting other data types to set.

- tuple():
   - It can use for creating a tuple or converting another data type to a tuple.

- frozenset():
   - It can use for creating a frozenset or converting other data types to frozenset.

- complex():
   - It can use for creating complex numbers or converting other number data types to complex numbers.
   - First parameter is the real side, the second parameter is the virtual side of the complex number.

- float():
   - It is using to convert integers and strings to floating numbers.

- int():
   - It is using to convert floating numbers and strings  to integers.
   - Also we can use for octal numbering system to decimal number system.
      ```python
         int('12', 8)    
         # output: 10
      ```

- str():
   - It is used to convert other data types to strings.
   - Its parameters are error and encoding.

- dict():
   - It is used for creating a dictionary or converting other data types to dictionaries.

- callable():
   - That function interrogates object is callable or not.

- ord():
   - That function gives to the decimal version of characters.

- oct():
   - That function is converting any numbers to the octal version.

- hex():
   - That function is converting any numbers to hexadecimal versions.

- Expressions are using code pieces to producing a value.
- Strings, Numbers, Operators, List Gen expressions.

- eval():
   - We can check bool values with this function because eval() function can take only expressions. 

- exec():
   - One Fucking Shitty Function.

- globals():
   - Shows gloabl effect functions.

- locals():
   - Shows local effect functions.

- compile():
   - The code object converts a string into an object that you can later call exec on to run the source code in the string.  

- copyright():
   - Shows copyrights of python.

- credits():
   - Shows who helped to develop python.

- license():
   - Show license of python.

- dir():
   - Show function's methods.

- divmod():
   - That function gives the quotient and remainder of the division process.

- enumerate():
   - We can sort and enumerate characters with that function.

- exit():
   - We can exit from the working program with that function.

- help():
   - It includes information about python and, we can call with help function.

- id():
   - That function shows identification of characters.

- input():
   - We can take data from users with that function.

- format():
   - That function working as .format() method of strings but more extensive.

- filter():
   - Explain from examples; 
      ```python 
         l = [400, 176, 64, 175, 355, 13, 207, 
         298, 397, 386, 31, 120, 120, 236, 241, 
         123, 249, 364, 292, 153] # Our list.

         # We can use list comprehensions to do shortly.
         [i for i in l if i % 2 == 1] 

         def tek(sayı):
            return sayı % 2 == 1  

         print(*filter(tek, l))  
         # Or we can use filter() function to do shortly.
      ```
      - Both of them same work. That function can filtered data types.

- hash():
   - It gives different values to some object types.

- isinstance():
   - That function working as type() function.
      ```python
         isinstance('function', str)  
         # output:True
      ```

- len():
   - We can count the length of objects with that function.

- map():
   - If we want to work with each unit of list/string/set/etc. , we can use this function.
      ```python
         list(map(function_name, our_datas)
      ```

- max():
   - That function gives greater unit in list/string/set/etc.
   - We can arrange greater value with ‘key=’ parameter.

- min():
   - That function gives lowest unit in list/string/set/etc.
   - We can arrange lowest value with ‘key=' parameter.

- open():
   - That function can create or open a file.
   - 'buffering=' parameter can arrange data waiting on buffer or not. (value of 1 is waiting for the value of 0 to continue.)
   - 'encoding=' parameter can decide to open a file with which character coding.
   - 'error=' parameter can stop programming when the program has an error.
   - If we don't want to stop the program, use the ignore parameter with it. Also, if we haven't anything with error parameters, python already enters strict with it.
   - ‘newline=’ parameter can decide to prefer which line end character.( windows end line = \r\n, linux = \n)
   - '.fileno()' method is giving numbers to file to identify them.
   - 'closefd=True/False': When we are closing any file, file identification is deleted but, if we use the closefd=False parameter, It continues to exist.

- pow():
   - We can calculate the power of numbers with these functions.
   - pow() function has three-parameter.
   - First one: Number, Second one: Power, Third one: Divide
   - Third parameter divide the number then give us what it is a reminder.

- print():
   - We use this function to send some messages to users.
   - degx parameter decides which value of our output.
   - sep parameter arranges which, characterizes putting between units.
   - end parameter arranges which characterizes putting after the last unit.
   - file parameter decides to out write where. The default output file is sys.stdout.
   - flush parameter arranges data waiting on buffer or not. ( default value is false but, if we change it to true, it writes directly to the file.

- quit():
   - We use this function to exit from any program.

-  range():
   - We use this function to sort numbers between some range.
   ```python
      range(start_point, end_point, jump_value)  
      # Jump value can be one by one , two by two ...
   ```

- reversed():
   - We can reverse data sorting with this function.

- sorted():
   - We can sort units with that function.
   - Also, we can arrange the value of sorting with key parameters.

- slice():
   - That function create a dividing value for objects.
   ```python
      slice(start_point, end_poimt, jump_value) 
      # Jump value can be one by one, two by two ...
   ```

- sum():
   - That function can add numbers.
   - It can take two-parameter.
   - Second parameter is what we want to add to the numbers list.

- type():
   - That function show object's type.

- zip():
   - That function matches the units.

- vars():
   - If we use without parameters, It gives us the same output with the locals() function.
   - If we use with parameter, It gives us the same output with dir() function.
