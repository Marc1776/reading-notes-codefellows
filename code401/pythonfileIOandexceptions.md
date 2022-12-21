# FileIO & Exceptions

## Why this matters

Developers constanly work with files, adjust files, read/write files and so on.  Seems pretty obvious to me.

Exceptions are going to be a big part of test driven development.  Need to know what the errors are or when code doesn't produce what I want it to or it should.  Knowing why something failed and when helps tremendously in debugging or problem-solving

## Read and write files in Python

A file is used to store data, can be a text or program.  3 main parts:  Header (metadata), Data (contents), and End of File or EOF (special character to indicate the end of the file)

File path is a string showing the location of the a file with 3 parts:  Folder Path (folder location), File Name (name of file), and Extension (the end of the file path after the .)

Encoding is a translation from data to human characters.

open()  will open a file and looks like: reader = open('notes.txt')

close() will close a file and looks like:  reader.close()

another way to close files is a 'with' statement:  with open('file.txt')

r = open for reading

w = open for writing

rb or wb = open in binary mode (read/write with data)

example opening a file:  open('file.txt', 'r')

readline (size x) will limit the line to x number of bytes per line that is read

readlines will return file as a list

[midway down the page for readline specific info](https://realpython.com/read-write-files-python/)

print(line, end='') the end='' prevents python from adding an additional newline to the text being printed and only prints what is being read from the file [defined here](https://realpython.com/read-write-files-python/)

.write(string) writes the string to the file

.writelines(seq) writes the sequence to the file, I must add line ending(s).

the byte reader can break down the data to determine that say a png image is actually a png image based on the data returned from the image in byte reader

## Exceptions in Python

Syntax error:  when the parser finds an incorrect statement

Exception error:  when python code syntax is correct, but results in an error

We can raise an exception by using raise to throw the exception if a condition occurs.

AssertionError exception:  assert that a condition is met, if the condition is true the program continues, but if it's false an AssertionError exception is thrown

try and except:  try runs the code normally, except statement is the response of the program to exceptions

else statements tell a program to execute certain code only in the absence of exceptions.

finally clause will always run a code regardless of exceptions

### Things I want to know more about

The file reading was more in depth than I can currently understand, especially towards the end of the article.

### Links or references

[Read/write python files video](https://realpython.com/courses/reading-and-writing-files-python/)
