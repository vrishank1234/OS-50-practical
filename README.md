# OS-50-practical

Networking
=================================================
1. UDP Client-Server Program
Description: Implements a simple UDP client-server program where the client sends a message and the server echoes it back, then both sockets are closed.
2. UDP Client-Server with Loop
Description: Modifies the UDP client-server program to handle multiple messages in a loop until the client sends "exit".
3. TCP Reverse String Server
Description: Implements a TCP client-server program where the server receives a string from the client, reverses it, and sends it back.
4. Multi-threaded TCP Reverse String Server
Description: Enhances the TCP reverse string server to handle multiple clients concurrently using threads.
5. TCP Even/Odd Server
Description: Implements a TCP client-server program where the server checks if a number received from the client is even or odd and sends the result back.
6. TCP Even/Odd Server with Loop
Description: Modifies the TCP even/odd server to handle client connections in a loop until the client sends "exit".
7. TCP File Transfer Server
Description: Implements a TCP client-server program where the client sends a file name and the server responds with the contents of the file.
8. Enhanced TCP File Transfer Server
Description: Modifies the TCP file transfer server to send a list of available files to the client before sending the requested file.
9. UDP Echo Server
Description: Implements a UDP client-server program where the server echoes back any message received from the client.
10. Multi-client UDP Server with select()
Description: Creates a UDP server that handles multiple clients using select() for I/O multiplexing.
File Handling
1. Read First 10 Bytes
Description: C program to open a text file and read the first 10 bytes.
2. Create, Open, and Close a File
Description: C program to create, open, and close a text file.
3. Read Last 10 Bytes
Description: C program to open a text file and read the last 10 bytes.
4. File Opening Modes
Description: C program demonstrating the use of 5 different modes to open a text file.
5. Write to a File
Description: C program to write "Hello, World!" to a new text file.
6. Append to a File
Description: C program to append "End of File" to an existing text file.
7. Read File Line by Line
Description: C program to read a file line by line and print each line.
8. Copy File Contents
Description: C program to copy the contents of one file to another.
9. Count Lines in a File
Description: C program to count the number of lines in a text file.
10. Check File Existence
Description: C program to check if a file exists before attempting to open it.
File Permissions and Commands
1. Using chmod System Call
Description: C program to demonstrate the use of chmod system call to set file permissions.
2. Using chown System Call
Description: C program to demonstrate the use of chown system call to change the owner of a file.
3. Using stat System Call
Description: C program to demonstrate the use of stat system call to get file status.
4. File Commands in Zsh
Description: Demonstrates 5 file commands on Zsh shell (e.g., cat, head, tail, cp, rm).
5. Directory Commands in Zsh
Description: Demonstrates 5 directory commands on Zsh shell (e.g., ls, mkdir, cd, rmdir, pwd).
6. List Files with Sizes
Description: Zsh script to list all files in the current directory with their sizes.
7. Delete .tmp Files
Description: Zsh script to find and delete all files with a .tmp extension.
8. Display Last 20 Lines of .log Files
Description: Zsh script to display the last 20 lines of all .log files in a directory.
9. Rename .txt Files to .bak
Description: Zsh script to rename all .txt files to .bak in a directory.
10. Directory Backup
Description: Zsh script to create a backup of a directory.
System Calls and IPC
1. dup System Call
Description: C program to illustrate the concept of dup system call.
2. fork System Call
Description: C program to illustrate the concept of fork system call.
3. wait System Call
Description: C program to illustrate the concept of wait system call.
4. signal System Call
Description: C program to illustrate the concept of signal system call.
5. IPC Using Pipes
Description: C program to demonstrate inter-process communication (IPC) using pipes.
6. IPC Using Message Queues
Description: C program to demonstrate IPC using message queues.
7. IPC Using Shared Memory
Description: C program to demonstrate IPC using shared memory.
8. IPC Using Semaphores
Description: C program to demonstrate IPC using semaphores.
9. Child Process Using exec()
Description: C program to create a child process that runs a different program using exec().
10. Handle SIGINT Signal
Description: C program to handle the SIGINT signal and print a message when it is received.
Text Processing
1. AWK Commands in Zsh
Description: Demonstrates 5 AWK commands on Zsh shell.
2. Print Second Column Using AWK
Description: AWK command to print the second column of a file.
3. Print Lines with Third Column > 50
Description: AWK command to print lines where the third column is greater than 50.
4. Sum First Column Using AWK
Description: AWK script to sum the values in the first column of a file.
5. Print Last Column Using AWK
Description: AWK script to print the last column of each line in a file.
6. SED Commands in Zsh
Description: Demonstrates 5 SED commands on Zsh shell.
7. Replace "foo" with "bar" Using SED
Description: SED command to replace all occurrences of "foo" with "bar" in a file.
8. Delete Lines Containing "error" Using SED
Description: SED command to delete lines containing the word "error" in a file.
9. Insert Line Before Third Line Using SED
Description: SED command to insert a line of text before the third line of a file.
10. Append Line After Fifth Line Using SED
Description: SED command to append a line of text after the fifth line of a file.
