
6# Exp.No:4e
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a python program to perform addition and multiplication operation using class and if..elif statement

note:
class name should be calc, function name should be setvalues( to set a and b values) ,add and mul
cases : 
* choice 1 ->perform addition ,
* choice 2-> perform multiplication ,
* choice 0 -> exiting, other choices -> print 'invalid choice'

---

### ALGORITHM

1. Begin the program.
2. Define the Class Calc:
   * Initialize the class with an __init__ method (optional, but good practice).
   * Define a method set_values(a, b):
      * Accept two parameters, a and b.
      * Store these values as instance attributes (e.g., self.a and self.b).. Terminate 
# Exp.No:4d  
## FILES - FREQUENCY OF CHARACTERS IN A FILE

---

### AIM  
To write a Python program that reads a file and counts the frequency of each character in it.

---

### ALGORITHM

1. Begin the program.  
2. Define the function `create_file()` that accepts two arguments:   
   - `file_path`: The path to the file.  
   - `content`: The string content to be written into the file.  
3. Open the file specified by `file_path` in write mode (`'w'`), and write the provided `content` into the file.  
4. Close the file (this is automatically done when exiting the `with` block).  
5. Define the function `character_frequency()` that accepts one argument:  
   - `file_path`: The path to the file whose character frequency is to be calculated.  
6. Open the file specified by `file_path` in read mode (`'r'`), and read its content into the variable `content`.

5. 
