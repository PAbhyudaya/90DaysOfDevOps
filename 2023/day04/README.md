# Day 4 Task: Basic Linux Shell Scripting for DevOps Engineers.

## What is Kernel

The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system. It manages communication between the hardware and the software. It provides a user interface, file system management, network services, and various utility applications that allow users to interact with the system.

## What is Shell

A shell is special user program which provide an interface to user to use operating system services. Shell accept human readable commands from user and convert them into something which kernel can understand. It is a command language interpreter that execute commands read from input devices such as keyboards or from files. The shell gets started when the user logs in or start the terminal.

## What is Linux Shell Scripting?

A shell script is a computer program designed to be run by a linux shell, a command-line interpreter. The various dialects of shell scripts are considered to be scripting languages. Typical operations performed by shell scripts include file manipulation, program execution, and printing text.

**Tasks**

- Explain in your own words and examples, what is Shell Scripting for DevOps

  - ```Shell Scripting:- writing series of linux cmds and executing them automatically by a Shell. Instead of typing cmds one by one, we can group them into single       script to automate repetative tasks. ```
  
- What is `#!/bin/bash?` can we write `#!/bin/sh` as well?
  
  - ``` The very first line of shell script that tells the OS which interpreter to use while executing the file.  ```
    
- Write a Shell Script which prints `I will complete #90DaysOofDevOps challenge`
  
  ` #!/bin/bash
   echo "I will complete #90DaysOofDevOps challenge" `
  
- Write a Shell Script to take user input, input from arguments and print the variables.

` #!/bin/bash
  echo "Enter your name: "
  read name
  echo "Enter your age: "
  read age
  echo "Arguments"
  city=$1
  country=$2
  echo "Name: $name"
  echo "Age: $age"
  echo "City: $city"
  echo "Country: %country"
  `
  
- Write an Example of If else in Shell Scripting by comparing 2 numbers

Was it difficult?

- Post about it on LinkedIn and Let me know :)

Article Reference: [Click here to read basic Linux Shell Scripting](https://devopscube.com/linux-shell-scripting-for-devops/)

YouTube Video: [EASIEST Shell Scripting Tutorial for DevOps Engineers](https://www.youtube.com/watch?v=_-D6gkRj7xc&list=PLlfy9GnSVerQr-Se9JRE_tZJk3OUoHCkh&index=3)

[← Previous Day](../day03/README.md) | [Next Day →](../day05/README.md)
