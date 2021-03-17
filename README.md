# Reverse Polish Calculator

# Installation instructions: (for windows)
1. Download main.exe file from bin folder.
2. Open command prompt and loacte your working directory to the directory where main.exe is saved.
3. Use command `main` and use the application.

# instructions to create executable file in your computer: (windows)
## 1. Using object codes (requirement: gnu compiler installed)
**
      i. Download main.o, stack.o, getch.o and getop.o files from bin folder.
      ii. Open command prompt and loacte your working directory to the directory where these are saved.
      iii. Use command `g++ -o main stack.o getch.o getop.o main.o` to get `main.exe` file
**
## 2. Using source cose (requirement: gnu compiler make utility installed)
      i.  Download main.cpp, stack.cpp, getch.cpp, getop.cpp calc.h and makeFile files from root folder.
      ii. Open command prompt and loacte your working directory to the directory where these are saved.
      iii. Use command `make` and `make clean` you will get the executable file `main.exe`.   
