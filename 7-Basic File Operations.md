- open() 
   - We can create a file with that function.
      ```pyton
         name = open(file_name, modal)
      ```
   - Also, we can define the location of the file.
      ```python
         dosya = open("/dosyayı/oluşturmak/istediğimiz/dizin/dosya_adı", "w")
         open(r"C:\aylar\nisan\toplam masraf\masraf.txt", "w") # Use r to pass from escape strings.
      ```
   - When we open a file with write modal, It crates an empty file for us.
   - If any same name file exits in that directory, It deletes that file then creates an empty file.
   
   - .write() Method:
      - If we want to write a file, we can use that method.
         ```python
            dosya.write("something")
         ```
   - .close() Method:
      - We can close files with that method.

   - We can open a file with "r" modal or without modals to reading.
      - .read() Method:
         - That method shows all things in the file with that method.
      - .readline() Method:
         - That method shows line by line all things in file with that method.
      - .readlines() Method:
         - We got all things in the file as a list.

- Changes From Files
   - "a" modal provides to change non-empty files.
   - File modals:
      - r: read
      - w: write
      - a: write (if the file exists, don't clear it. Just writing up.)
      - x: execute (if the file exists, it sends you an error message.)
         
