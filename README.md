# Shell Permissions
This project contains multiple tasks related to shell permissions

## task0: My name is Betty
- **Description**: This script switches the current user to the user 'betty'.
- **Command**: 'su betty'

## task1: Who am I 
- **Description**: This script prints the effective username of the current user.
- **Command**: 'whoami'

## task2: Empty!
- **Description**: This script creates an empty file called 'hello'.
- **Command**: 'touch hello'

## task3: Execute
- **Description**: This script adds execute permission to the owner of the file 'Hello'.
- **Command**: 'chmod u+x hello'

## task4: Multiple permissions
- **Description**: This script adds execute permission to the owner and the group owner, and read permission to others, to the file 'hello'.
- **Command**: 'chmod ug+x,o+r hello'

## task5: John Doe
- **Description**: This script sets the mode of the file hello.
- **Command**: 'chmod 753 hello'
