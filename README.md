# hello-go

Hello, World!

This is a simple go program with a default output.

This program can also accept multiple arguments for custom outputs.

## Installation

Clone this repository onto your machine

```
git clone https://github.com/Andrew-R-Lawler/hello-go.git
```

# Windows

```
cd hello-go/cmd/
go build -o hello.exe
mv hello %USERPATH%\go\bin
```

# Linux

```
cd hello-go/cmd/
go build -o hello
mv hello /usr/bin/
```

## Usage

call the exe from the command line alone or with multiple arguments

# Without Arguments

```shell-session
root@user:~$ hello
Hello, World!
```

# With Arguments

```shell-session
root@user:~$ hello Andrew Leah
Hello, Andrew, Leah!
```
