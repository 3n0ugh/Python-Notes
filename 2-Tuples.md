- They seem like lists.
- Tuples are immutable.

- To Define Tuple
   ```python
      Marks = ("BMW", 8 , "Fiat" , "Renault", 9)
      Marks = "BMW", 8 "Fiat", "Renault", 9
   ```
   - Also we can use tuple() function to define a tuple.
      ```python
         tuple(["John", "Patrick", 9, "Alice"])
      ```

- To Define One Unit Tuple
   - Just use a comma after unit.
      ```python
         marks = "BMW",
         marks = ("BMW")
      ```
- To Reach Tuple Units
   - It is like list or strings.
      ```python
         Marks[0]
         # output: "BMW"
      ```
- To Add an Unit to Tuple
   - If you add a unit to tuple, Just re-define the tuple.
      ```python
         Marks = ("BMW", 8 , "Fiat" , "Renault", 9)
         Marks = Marks + "Mercedes Benz" #  If we try to add an strings , we got a error. Because just we can add a tuple type units.
         Marks = Marks + ("Mercedes Benz")
      ```