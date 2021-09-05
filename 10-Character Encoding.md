
 - Character encoding is a converting process.
 - Computers are perceived electrical signals then  meaning them to 0 and 1.  (about voltage)
 - If we want to encode something, we convert them to readable things using 0 and 1.

- ASCII
   - American Standart Code for Information Interchange
   - It was designed by Bob Bemer and his crew.
   - We can see ASCII table from here [ASCII](https://www.asciitable.com/) 

    

- 7 Byte System
   - First 7 bytes are epitomizing 127 characters.
   - ASCII is taking a step for secure information gathering.
   
- UNICODE
   - UNICODE is a standard as ASCII.
   - It is starting a design by Joe Becker, Lee Collins, and Mark Davis.

- .encode method's errors parameters
   - ![](https://github.com/3n0ugh/Python-Notes/blob/main/Pasted%20image.png)
   ```python
      "bu Türkçe bir cümledir.".encode("ascii", errors="strict")
   ```
- repr() Function
   - We can see backend working with repr() function.

- ascii() Function
   - It shows character's unicode code points.

- ord() Function
   - It gives to us a character's number equivalent.

- chr() Function
   - It gives to us a number's character equivalent.
