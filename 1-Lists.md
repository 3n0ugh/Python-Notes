- We will use square brackets ([]) to define lists.
   ```python 
      Cities = [ "Berlin", "London", "Istanbul", "Washington D.C."]
   ```

- Lists can include different data types like integer, strings , floating numbers.
   ```python
     List = ["Car", "32", "5.8"]
   ```

- List also contains another lists.
   ```python
     List = ["Car", ["Berlin", "London", "Istanbul"], "32", "5.8"]
   ```

- We can create empty list.
   ```python
     List = []
   ```

- Sometimes we can get list output from another source.
   ```python
      School = "Heybeliada Deniz Lisesi"
      School.split()
      # output: ['Heybeliada', ‘Deniz’, ‘Lisesi’]
   ```
   
- As we can see i variables create a double unit list. Also we separate units to parameters.
with star sign (*). We can write like print(range(i[0], i[1])), if we don't use star sign.


- split() Method
   - Remember we can use split() method for separate to strings. We can see above example.
   - if we try to use split methods we parameters like : split("i"), our output seem like:
   ```python
      characters = "asdfaskjfhlasfisajdkfhasl"
      print(characters.split("i"))
      # output: ['asdfaskjfhlasf', 'sajdkfhasl']
   ```

- list() Function
   - If we want to seperate all units of string, We will use list() function.
   ```python
      print(list(characters))
      # output: ['a', ‘s’, ‘d’ , ‘f’ , ‘a’, ‘s’, ‘k’, ‘j’, ‘f’, ‘h’, ‘l’, ‘a’, ‘s’, ‘f’, ‘i’, ‘s’, ‘a’, ‘j’, ‘d’, ‘k’, ‘f’, ‘h’, ‘a’, ‘s’, ‘l’]
   ```
   - If we want to get numbers with range() function, we can do it with list() function.
   ```python
      print(list(range(6,12)))
      # output: [6, 7, 8, 9, 10, 11, 12]
   ```
   
- Access to List Units
   - It is like strings. Lists have queue and it is begining from 0.
   ```python
      fruits = ["apple", "peach", "apricot", "melon", "strawberry"]
      print(fruits[0])
      # output: ‘apple’
   ```
   - If we want to take last unit of list, use list_name[-1].
   - To write a reverse version of list using list_name[::-1]
   - To divide list units using list_name[a:b]
      - a is which unit first we want,
      - b is which unit we want +1.
   - If you want to get list of list unit, use list_name[number][number]
  
- To Change List Units
   - Lists are mutable.
   - If we change a unit, first we need to learn queue of that unit.
   - Then: 
   ```python
      fruits[0] = "cherry"
   ```
   - Now our fruits variable has not apple unit. But it's first unit is cherry.
   - To change between some queue in list we can use this 
   ```python
      list[0:len(list)] = 9, 8, 7
   ```
   - To change all list units use this 
   ```python
      list_name[:] = x, y, z, t
   ```

- To Add List Unit
   - If you want to add a unit to list , it's type must be list.
   - use : 
   ```python
      list_name[] += ["anything"]
   ```

- To Combine Lists
   - Just use plus between which lists you want to combine.
   ```python
      atesli_tabak = meyveler + fruits
   ```
      
- To Subtract List Units
   ```python
      del list_name[queue]
   ```

- To Delete Lists
   ```python 
      del list_name
   ```
- To Copy Lists
   ```python
      list1 = lits2[:]
   ```

- List Comprehensions
   -  It is provide to us write for loops on single line.
      ```python
         ortak = [z for i in foods for z in i] 
         for z in foods:
            for z in i:
               ortak += [z]
      ```