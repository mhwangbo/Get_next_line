# Get_next_line
A function to read a line ending with a newline character from a file descriptor.

## Mandatroy part
    - Write a function that returns a line read from a file descriptor.
    - A "line" is a succession of characters that end with '\n' or with End Of File.
    - Prototype
      - int get_next_line(const int fd, char **line);
      - The first parameter is the file descriptor that will be used to read.
      - The second parameter is the address of a pointer to a character that will be used to save the line read from the file descriptor.
      - The return value can be 1, 0 or -1 depending on whether a line has been read, when the reading has been completed, or if an error has happened respectively.
    - get_next_line must return its result without ’\n’.
    - Global variables are forbidden
    - Static variables are allowed
