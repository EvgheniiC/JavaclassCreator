# JavaclassCreator
library for automatic generation of  .java classes

Create a library for automatic generation of classes in the editor.
The library should allow:
  - generation of a .java file (class) based on the values of the entered field names and their types.
  - generation of setter / getter for fields.
  - constructor generation.
  - spelling imports
 
  The data for generating the class must be taken from text files from a specific directory, the path to which must be specified.
  Each line in a text file has the format:
 
  Name: name of class; Fields: name, type (example java.lang.String);
  
  Alternatively, you can use CSV instead of text files. 
