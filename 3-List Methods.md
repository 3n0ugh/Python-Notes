- We can see list methods with dir(list) function.
- .append() Method:
   - We use this method for to add any unit to lists.
   - We can't add more than one unit.

- .extend() Method:
   - It has just a difference between .append() method and .extend() method.
   - .extend() method can add multiple units.
   
- .insert() Method:
   - It can add unit which queue we want.
      ```python
         liste.insert(queue , unit)
      ```

- .remove() Method:
   - It can delete any unit from lists.
      ```python
         liste.remove(unit)
      ```

- .reverse() Method:
   - We can reverse lists with .reverse() method or reversed() function.

- .pop() Method:
   - It is like .remove() method.
   - If we use with parameter, it delete which number we write for parameter.

- .sort() Method:
   - This method arrange list units.
   - It has reverse parameter.
      ```python
         name.sort(reverse=True)
      ```
      
- .index() Method:
   - This method give to us which unit we write for parameter's location.
      ```python
         liste.index("armut")
         # output: 2
      ``` 
      
- .count() Method:
   - That method say to us how many same unit include the list.
      ```python
         liste.count("armut")
         # output:0
      ```   
      
- .copy() Method:
   - As you see from name that method it can copy the lists.
      ```python
         list2 = list1.copy()
      ```
      
- .clear() Method:
   - That method conver list to empty list.
   