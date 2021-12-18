# Process Control Block

Process Control Block is a data structure that contains information of the process related to it. The process control block is also known as a task control block, entry of the process table, etc.

It is very important for process management as the data structuring for processes is done in terms of the PCB. It also defines the current state of the operating system.

# Structure of the Process Control Block

The process control stores many data items that are needed for efficient process management. Some of these data items are explained with the help of the given diagram

<img src='./img/pcb.png' />

# Some of the important data items in the process control block

- Process State - This is the current state of the process. It can be either ready, running, waiting, terminated, etc.

- Process Number - This is the process number assigned to the process. It is used to identify the process.

- Program Counter - This is the current instruction pointer of the process. It is used to identify the current instruction being executed.

- Registers - This is the register file of the process. It contains the values of the registers.

- Memory Limits - This is the memory limits of the process. It contains the starting and ending address of the memory.

- List of Files - This is the list of files that are opened by the process.
