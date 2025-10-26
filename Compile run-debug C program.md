Compile run/debug C program via cmd terminal

1. to compile RELEASE version: 
    **gcc -I../Include file1.c file2.c file3.c main.c -o sort_application**

    explanation: -I include folder path with libraries/header files (listed as #include <.... .h>

    file1, file2 are file names to be compiled (manual linking), they all have #include to reference within

    -o output file named sort_application (will come out as sort_application.exe)


3. to compile DEBUG version:

    **gcc -g -I../Include file1.c file2.c file3.c main.c -o sort_application**

    explanation: same as release, except -g enables debugging


4. run program

    3a. release version: **sort_application.exe**
  
    3b. debug version:   **gdb sort_application.exe**
