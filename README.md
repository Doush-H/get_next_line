# get_next_line
This is one of the projects in the curriculum of 42 School.

## The goal of the school
The schools concept relies on you teaching yourself by learning how to do research and ask for help of your peers when needed. There are no teachers nor lectures. The curriculum includes planty of projects that you need to finish in order to progress and finish the school. The projects increase in difficulty as you go. Main programming language used in the school is `C` and on later stages of the curriculum `C++` besides these two you also learn about other stuff like: `Docker`, `Virtual Machines`, `networking` and more.

## The goal of the project
In this project I needed to create a function that can be used to read lines of text from a given file descriptor.

## In this project I learned about:
  - How does the `read()` function work
  - What are `file descriptors`
  - How to `open files` for `reading` and `writing`
  - `Static variables` in C
  
## How to use it?
Copy the .c files into your project and include the header file. Function prototype is as follows `char *get_next_line(int fd)`. When compiling your project you can specify the `-D BUFFER_SIZE=*size to read*`, `size to read` (*by default it's assigned to 1 in the header file*) can be used in order reduce the system calls to `read()` as it will determine how many bytes are read in each call to `read()` function.
