→ Decimal
   ⇒ We can count numbers with power of 10.
      • >>> (0 * (10 ** 0)) + (8 * (10 ** 1)) + (9 * (10 ** 2)) + (1 * (10 ** 3)) 
      • output: 1980

→ Octal
   ⇒ It can include 8 number. (0, 1, 2, 3, 4, 5, 6, 7)
   ⇒ We can count numbers with power of 8.

→ Hexdecimal 
   ⇒ It has 16 symbol. (0, 1, 2, 3, 4, 5, 6, 7, 8, 9, a, b, c, d, e, f)
   ⇒ We can count numbers with power of 16.
      • >>> ((12 * (16 ** 0)) + ((11 * (16 ** 1)) + ((7 * (16 ** 2))
      • output: 1980 = '7bc'

→ Binary
   ⇒ It has just 2 symbol. (0, 1)
   ⇒ We can count numbers with power of 2.
      • (0 * (2 ** 0)) + (0 * (2 ** 1)) + (1 * (2 ** 2)) + (1 * (2 ** 3)) 
      • output: 12

→ Converting Counting Systems
 
   ⇒ bin()
      • Give to number's  binary form.
      • 0b mean is the number from binary.
   
   ⇒ hex()
      • It convert numbers to hexdecimal form.
      • 0x mean is the number from hexdecimal.

   ⇒ oct()
      • It convert numbers to octal form.
      • 0o mean is the number from octal.
   
   ⇒ int()
      • It convert to numbers to integer form.
      
   ⇒ {:b}.format(number) = binary
   ⇒ {:x}.format(number) = hexdecimal
   ⇒ {:o}.format(number)  = octal