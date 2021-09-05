- Lambda Functions:
   - This function works like the def() function. It defines functions.
      ```python
         function = lambda parameter1, parameter2: parameter1 + parameter2
         def function(args1, args2):
           return args1 + args2
      ```

- Recursive Functions:
   - It can call the function in itself.
   - While we are using this function, we need to decide the border of the function's depth.
   - When exiting from recursive progress, it makes the reverse form of the object.

- Nested Functions:
   - It includes another function.
   - We created a local function with a nested function. Because when we define a function in another function, System can't know the inside function before calling inclusive function.
   - If we want to change the global variable, we must use a global statement.
   - If we want to change the inclusive function's variable, we are using a nonlocal statement.

- Generators:
   - Difference between return and yield statement is local variable deletion. 
   - Generators can use with for loop.
      ```python
         for i in fibonacci():
            print(i)
      ```
      ```python
           yield from a_generator:
        above statement equals to:
            for i in a_generator:
                 yield i
      ```
   - List and dictionary generators are just one-time useable. If we use them once, we can't use them again because it gives 'none' output.
  
