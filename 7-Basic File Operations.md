→ open() 
   ⇒ We can create a file with that function.
      • name = open(file_name, modal)
   ⇒ Also we can define the file's location.
      • dosya = open("/dosyayı/oluşturmak/istediğimiz/dizin/dosya_adı", "w")
      • open(r"C:\aylar\nisan\toplam masraf\masraf.txt", "w") => Use r to pass from escape strings.
   ⇒ When we open a file with write modal, It crates a empty file for us.
   ⇒ If any same name file exits in that directory, It first deletes that file then create empty file.
   
   ⇒ .write() Method:
      • If we want to write a file, we can use that method.
         ◇ dosya.write("something")
   
   ⇒ .close() Method:
      • We can close files with that method.

   ⇒We can open an file with “r" modal or without modals to reading.
      • .read() Method:
         ◇ That method shows all things in the file with that method.
      • .readline() Method:
         ◇ That method shows line to line all things in file with that method.
      • .readlines() Method:
         ◇ We got all things in the file as list.

→ Changes From Files
   ⇒"a" modal provides to change non-emtpy files.
   ⇒ File modals:
      • r : read
	  • w : write
	  • a : write (if the file exist, don't clear it. Just writing up.)
	  • x : execute (if the file exist, it sends to you a error message.)
         