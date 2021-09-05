- To define a byte, write:
   ```python
      b"anything"
   ```
- bytes() Function
   - we can create byte characters with which encoder.
      ```python
         b = bytes("s", "utf-8")
      ```
- bytes() Methods
   - .decode() Method
      - We can reverse a encoding characters to strings.
   - .fromhex() Method
      - hexdecimal characters to byte.

- Byte arrays are immutable. If you want to change any byte array, you need to define it again.
- To create a byte array, use the bytearray() function.
   ```python
      bytearray(b"PDF-1.7")
   ```
