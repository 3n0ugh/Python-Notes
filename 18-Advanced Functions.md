→ Lambda Functions:
   ⇒ This function works like def function. It define functions.
      • >>> function = lambda parameter1, parameter2: parameter1 + parameter2
      • >>> def function(args1, args2):
      •  >>>     return args1 + args2

→ Recursive Functions:
   ⇒ It can call function in itself.
   ⇒ While we using this function, we need to decide border of function's depth.
   ⇒ When exit from recusive progress, it make reverse form of object.

→ Nested Functions:
   ⇒ It includes another function.
   ⇒ We created local function with nested function. Because when we define a function in another function, System can't know the inside function before calling inclusive function.
   ⇒ If we want to change global variable, we must use global statement.
   ⇒ If we want to change inclusive function's variable, we using nonlocal statement.

→ Generators:
   ⇒ Difference between return and yield statement is local variable deletion. While we are using return in any function, Function is finishing and local variables are deleting. But yield statement don't work like that.
   ⇒ Generators can using with for loop.
      • example: for i in fibonacci():
         ◇ print(i)
      • Yani:
           yield from bir_üreteç
        ifadesi bu ifade eş değerdir:
            for i in bir_üreteç:
                 yield i

   ⇒ List and dictionary generators are just one time useable. If we using them one time, we can't use again because it is giving ‘none’ output.
  