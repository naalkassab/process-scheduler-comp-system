# process-scheduler-comp-system
This is an implementation of a process scheduler of a computer system. 

# Important note 

Before running the Java program, the correct input file destination must be provided in line 87. Please enter this before running the file. 

# Data structures used in this program: 

There are two main data structures used to implement this program. An array list used to store the text file inputs as processes and priority queue used to execute each process based on highest priority. 
This is easiest explained by looking at where the program begins. In the main method the first data structure used is an array list “processes” used to store processes. This array list is created by reading into the input text file, parsing through the data, and storing them according to the process class. 

A priory queue “Q” is used to add processes from the array list “processes”. This priority queue is used to determine which process is the highest priority (the one with the lowest priority value) and should be executed.

The program would take a process from the array list that has the earliest arrival time and would then insert it into the queue. 

There are two main while loops, the first one focuses on emptying the array list data structure, while the other is focusing on emptying the priority queue data structure. 


