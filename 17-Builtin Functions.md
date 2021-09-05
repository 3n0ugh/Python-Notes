erators, Another Data Types, Dictionary Generators, Set Generators, Functions all of them are→ abs():
   ⇒ This function is giving any number's absolute value.
   ⇒ >>> abs(-20)   → output: 20
   ⇒ Also it can take just a parameter.

→ round():
   ⇒ This function round up the numbers.
   ⇒ Also if we give second parameter, we can arrange sensitivity of round upping.

→ all():
   ⇒ If all units bool values are true, it gives to us true value but if at least one unit is false, it gives to us false value.
   ⇒ We can use this function to control bool values of codes.

→ any():
   ⇒ If at least one unit has true value, This function gives to us true value but if it hasn't any true value unit, it gives to us false value.
   ⇒ We can use this function to control bool values of codes.

→ ascii():
   ⇒ It gives to us any object format to print screen.
   ⇒ Also it gives unicode version of Turkish characters.

→ repr():
   ⇒ Same work with ascii() but it gives to us non ascii characters with character versions.

→ bool():
   ⇒ It gives bool value of objects.

→ bin():
   ⇒ That function gives any numbers equivalent in binary system.

→ bytes():
   ⇒ That function converts other data types to byte data type.
   ⇒ If you enter a number as a parameter, function gives to us byte object amount of what we entered.
   ⇒ When we want to convert strings to byte data type, we are entering a encoding paramete as second parameter.
      • example: bytes('light', ‘utf-8’)
      • also we can use like : bytes('light', encoding='ascii')
   ⇒ If our entered string not define from encoder, we got UnicodeEncodeError error.

→ bytearray():
   ⇒ Working like bytes() but byte arrays are mutable data types.

→ chr():
   ⇒ That function converts integer to characters.
   ⇒ While converting integer, it take as base the UNICODE.

→ list():
   ⇒ It can use for creating a list or converting another data types to list.

→ set():
   ⇒ It can use for creating a set or converting another data types to set.

→ tuple():
   ⇒ It can use for creating a tuple or converting another data types to tuple.

→ frozenset():
   ⇒ It can use for creating a frozenset or converting another data types to frozenset.

→ complex():
   ⇒ It can use for creating a complex numbers or converting another number data types to complex numbers.
   ⇒ First parameter is real side, second parameter is virtual side of complex number.

→ float():
   ⇒ It is using to convert integer and strings to floating numbers.

→ int():
   ⇒ It is using to convert floating numbers and strings  to integers.
   ⇒ Also we can use for octal numbering system to decimal number system.
      • example: int('12', 8)    output: 10

→ str():
   ⇒ It using to convert another data types to strings.
   ⇒ It's parameters are error and encoding.

→ dict():
   ⇒ It is use for creating a dictionary or converting another data types to dictonaries.

→ callable():
   ⇒ That function interrogates object is callable or not.

→ ord():
   ⇒ That function gives to decimal version of characters.

→ oct():
   ⇒ That function is converting any numbers to octal version.

→ hex():
   ⇒ That function is converting any numbers to hexdecimal version.

→Expressions are using code piece to producing a value.
→Strings, Numbers, Operators, List Gen expressions.

→ Statement is a big notion including expressions.

→ eval():
   ⇒ We can check bool values with this function because eval() function can take only expressions. 

→ exec():
   ⇒ One Fucking Shitty Function.

→ globals():
   ⇒ Shows gloabl effect functions.

→ locals():
   ⇒ Shows local effect functions.

→ compile():
   ⇒ The code object converts a string into an object that you can later call exec on to run the source code in the string.  

→ copyright():
   ⇒ Shows copyrights of python.

→ credits():
   ⇒ Shows who helped to develop python.

→ license():
   ⇒ Show license of python.

→ dir():
   ⇒ Show function's methods.

→ divmod():
   ⇒ That function gives quotient and remainder of division process.

→ enumerate():
   ⇒ We can sort and enumerate characters with that function.

→ exit():
   ⇒ We can exit from working program with that function.

→ help():
   ⇒ It include information about python and we can call with help function.

→ id():
   ⇒ That function shows identification of characters.

→ input():
   ⇒ We can take data from user with that function.

→ format():
   ⇒ That function working as .format() method of strings but more extensive.

→ filter():
   ⇒ Explain from examples; 
      • l = [400, 176, 64, 175, 355, 13, 207, 298, 397, 386, 31, 120, 120, 236, 241, 123, 249, 364, 292, 153]           #Our list.
      • [i for i in l if i % 2 == 1]    #We can use list comprehesions to do shortly.
      • def tek(sayı):     return sayı % 2 == 1  print(*filter(tek, l))  #Or we can use filter() function to do shortly.
      • Both of them have same work. That function can filtered data types.

→ hash():
   ⇒ It gives different values to some object types.

→ isinstance():
   ⇒ That function working as type() function.
      • Example: isinstance('function', str)  output:True

→ len():
   ⇒ We can count lenght of objects with that function.

→ map():
   ⇒ If we want to work with each unit of list/string/set/etc. , we can use thist function.
      • example: We define a function than;
         ◇ >>>list(map(function_name, our_datas)

→ max():
   ⇒ That function gives greater unit in list/string/set/etc.
   ⇒ We can arrange greater value with ‘key=’ parameter.

→ min():
   ⇒ That function gives lowest unit in list/string/set/etc.
   ⇒ We can arrange lowest value with ‘key=' parameter.

→ open():
   ⇒ That function can create or open a file.
   ⇒ 'buffering=' parameter can arrange datas waiting on buffer or not.(value of 1 is wait, value of 0 continue.)
   ⇒ ‘encoding=’ parameter can decide open a file with which charachter coding.
   ⇒ ‘error=’ parameter can stopped programming, when program has error.
   ⇒ If we want to program don't stop, use ignore with it. Also if we don't anything with error parameter, python already enter strict with it.
   ⇒ ‘newline=’ parameter can decide to prefer which line end character.( windows end line = \r\n, linux = \n)
   ⇒ ‘.fileno()’ method is giving numbers to file for identificate them.
   ⇒ ‘closefd=True/False’ : When we are closing any file , file identificator deleted but if we use closefd=False parameter, It continue be exist.

→ pow():
   ⇒ We can calculate power of numbers with this functions.
   ⇒ pow() function has three parameter.
   ⇒ First one : Number , Second one : Power, Third one : Divide
   ⇒ Third parameter divide the number than give to us what it is reminder.

→ print():
   ⇒ We use this function to send some messages to users.
   ⇒ degx parameter decides which value of our output.
   ⇒ sep parameter arranges which character putting between units.
   ⇒ end parameter arranges which character putting after last unit.
   ⇒ file parameter decides to out write where. Default output file is sys.stdout.
   ⇒ flush parameter arrages datas waiting on buffer or not.( defaul value is false but if we change to true, it writes directly to file.

→ quit():
   ⇒ We use this function to exit from any program.

→  range():
   ⇒ We use this function to sort numbers between some range.
   ⇒ >>>range(start_point, end_point, jump_value)  #Jump value can be one by one , two by two ...

→ reversed():
   ⇒ We can reverse data sorting with this function.

→ sorted():
   ⇒ We can sort units with that function.
   ⇒ Also we can arrange value of sorting with key paramater.

→ slice():
   ⇒ That function create a dividing value for objects.
   ⇒ slice(start_point, end_poimt, jump_value) #Jump value can be one by one, two by two ...

→ sum():
   ⇒ That function can addition numbers.
   ⇒ It can  take two parameter.
   ⇒ Second parameter is what we want to add in numbers list.

→ type():
   ⇒ That function show object's type.

→ zip():
   ⇒ That function matches the units.

→ vars():
   ⇒ If we use without parameters, It gives to us same output with locals() function.
   ⇒ If we use with parameter, It give to us same output with dir() function.