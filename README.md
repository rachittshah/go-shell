# go-shell
A UNIX shell written in go

This CLI program is written in Go and can execute command line commands on your operating system. The program provides a command prompt that accepts commands as input, executes them and returns the output on the command line.

# Installation
To install the program, follow the below steps:

- Clone the repo
- Build the binary using ```go build main.go```
- Run the binary using ```go run .``` or ```go run main.go```

# Usage

To use the program, open the command prompt and navigate to the directory where the program is installed. Run the program by executing the compiled executable file. The command prompt will appear, allowing you to enter commands.

The program supports the following built-in commands:

```cd```: Change the current directory.
```exit```: Exit the program.

To execute other commands, simply enter them on the command prompt. The program will execute the commands and return the output on the command line.

# Notes
The cd command requires a path argument, and an error will be returned if it is not provided.
The program sets the output device to the command line. If you want to redirect the output to a file or another device, you can modify the program accordingly.
If you encounter any errors while using the program, they will be displayed on the command line.
