# __SHELL SCRIPTING__
## Intoduction

### __what is kernel?__
handles interactions btwn the shell and the hardware.
kernel is inside the OS, it takes commands from the shell and
the commands are forwarded to the kernel which talks to the hardware. shell and the kernal makes the  OS eg linux DOS mac. shell and the applications in your computer makes up the software

### __what is shell?__
it interpretes a command and passes the instructions to the kernel/OS

how do you find your shell?
### __how do you find your shell?__
run the command
```bash
echo $0
```

### __how are you able to know the available shells?__
```bash
cat /etc/shells
```
### __how do you get info about your shell?__
```bash
cat /etc/passwd
```

### __what is shell scripting?__
is the process of writing a scriptfile of the shell
it works as an interpreter


### __types of shells?__
1. Gnome - it is a graphical env(GUI) in linux

1. KDE - it is also a GUI

1. sh(shell) - user is given a shell to work if user creates and account. also known as bourne shell

1. Bash(unixshell) - meaning Born Again shell
1. ksh 
1. csh


### __how to start a shell?__
open the terminal to enter the bash shell

### __how do u change into a different shell?__
just type the name of the shell(available) and press enter. If a shell is not installed it will not work.
1. for sh
```bash
sh
```
to exit:
```bash
exit
```

### __how to run a shell script?__
you can use relative path or absolute path to run shell scripts
