- Sets:
   - To create a set:
      ```python
         set(["anything"])
      ```
   - Or first create a list then:
      ```python
         set(list_name)
      ```
   - Or we can use tuples:
      ```python
         set(tuple_name)
      ```
   - Or we can use strings:
      ```python
         set("anything")
      ```
   - Or we can use dictionaries:
      ```python
         set(dictionary_name)
      ```
   - But we can't use an integer to create a set.
   - Also, we can create like that:
      ```python
         {"something", "anything", "nothing"}
      ```
   - If we try to convert dictionaries to set, we will lose values.
   But if we will do like this;
      ```python
         liste = [(anahtar, değer) for anahtar, değer in bilgi.items()] 
         küme = set(liste)       #we will save both of them.
      ```
   - Sets can't include more than one same unit. So if you entered more than one same unit, sets will be delete them.
   - Set object does not support indexing.
   - .clear() method is clearing the sets.
   - .copy() method is copying the sets.
   - .add() method is adding unit to sets.
   - Just we can add only immutable data types.
   - .difference() method tell to us difference between in sets.
   - .difference_update() method tell difference then update first set. 
   - .discard() method can delete unit of set. If we try to delete any none-unit of set, we didn't get any error.
   - .remove() method can delete unit of set. If we try to delete any none-unit of set, we got a error.
   - .intersection() method is giving to us same unit of different sets. Also using “&” sign.
   - .intersection_update() found same unit of different sets then delete except same units.
   - .isdisjoint()  interrogate to intersection sets are empty or not.
   - .issubset() interrogate to subsset or not.
   - .issuperset() interrogate to superset or not.
   - .union() combines two sets.
   - .update() same work like .add() method.
   - .symmetric_difference() give to us what units are not include in both of sets.
   - .symmetric_difference_update() deletes intersection of sets.
   - .pop() deletes unit of sets randomly.

- Frozensets:
   - To create a frozenset:
      ```python
         frozenset(["anything"])
      ```
   - Same methods with sets.
   - Frozen sets are immutable.
