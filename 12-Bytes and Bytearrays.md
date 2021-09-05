→ To define a byte write => b"anything"

→ bytes() Function
   ⇒ we can create byte characters with which encoder.
      • b = bytes("s", “utf-8”)

→ bytes() Methods
   ⇒ .decode() Method
      • We can reverse a encoding characters to strings.
   ⇒ .fromhex() Method
      • hexdecimal characters to byte.

→ Bytearrays are immutable. If you want to change any bytearray, you need to define again.
→ To create a bytearray we use bytearray() function.
   ⇒ >>> bytearray(b"PDF-1.7")