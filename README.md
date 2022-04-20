# Advanced-Programming-Formative-Assessment

To enable a program to function each time it runs there needs to be an external and persistent data storage system that retains the state of the data. There are two considerations here. The physical storage medium for the data, such as a file or database and the format/structure of the data such as CSV or XML. This week you have explored a number of different formats in both regards as follows:
  CSV
  XML
  JSON
  MongoDB
  SQL Database
  Other file formats?

Select ONE format that you consider as most suited to the data in the scenario and the aims of the program. The format selected should support both the nature of the data and the aims of the application being designed. It should provide distinct advantages and minimal limitations over other data formats. It should not be selected solely because it is the easiest to program, although this can be included as an advantage if applicable.

Implement a parser that reads in the original data file. You may want to create a subset of the data file for testing and speed. Your program should then perform the translation from the original format/structure into your selected format. The result of this process should then be outputted to its relevant physical medium (files/database).

At this stage there is no requirement to handle data types (other than those inherent in the data format, i.e. numbers and “Strings”, conversions or missing data. The program can be demonstrated as a simple console based application, requiring the input of the file name by the user and sufficient output to demonstrate the correctness of the translation process.

Your program should produce regular output statements to the console so that it is easy to follow what the program is doing and provides a visual demonstration of the translation process. This will also be handy for any debugging required.
