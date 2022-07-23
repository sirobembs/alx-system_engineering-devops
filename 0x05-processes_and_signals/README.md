0x05-processes_and_signals

Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What is a PID:  A PID (i.e., process identification number) is an identification number that is automatically assigned to each process when it is created on a Unix-like operating system.

What is a process: A process is an executing (i.e., running) instance of a program. Each process is guaranteed a unique PID, which is always a non-negative integer.

How to find a process’ PID: echo $$

How to kill a process: SIGKILL

What is a signal: Signals are software interrupts. They provide a way for the user (or a process) to directly communicate with a process.

What are the 2 signals that cannot be ignored: SIGKILL and SIGSTOP cannot be ignored. 

Requirements
General
Allowed editors: vi, vim, emacs
All your files will be interpreted on Ubuntu 20.04 LTS
All your files should end with a new line
A README.md file, at the root of the folder of the project, is mandatory
All your Bash script files must be executable
Your Bash script must pass Shellcheck (version 0.7.0 via apt-get) without any error
The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
The second line of all your Bash scripts should be a comment explaining what is the script doing
