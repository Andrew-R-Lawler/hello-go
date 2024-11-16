# hello-go

Hello, World!

This is a simple go program with a default output.

This program can also accept multiple arguments for custom outputs.

## Installation

Clone this repository onto your machine

```
git clone https://github.com/Andrew-R-Lawler/hello-go.git
```

### Windows

to make it executeable globally on the command line for windows you need to build it with the .exe file type in the name and then move it to your go binaries folder

```
cd hello-go\cmd\
go build -o hello.exe
mv hello %USERPATH%\go\bin
```

### Linux

to make your program executable globally on the command line for linux you need to build your file and move it to the user binaries directory

```
cd hello-go/cmd/
go build -o hello
mv hello /usr/bin/
```

## Usage

call the exe from the command line alone or with multiple arguments

### Without Arguments

```shell-session
root@user:~$ hello
Hello, World!
```

### With Arguments

```shell-session
root@user:~$ hello Andrew Leah
Hello, Andrew, Leah!
```
