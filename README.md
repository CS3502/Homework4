# Homework4
Implement Banker's algorithm

Write a java class to implement banker's algorithm.
# Input: a file named **input.txt**
<p>
input.txt file is described as below.<br/>
First line, an integer 0< m <= 10, means the number of processes.<br/>
Second line, an integger 0< n < 10, means the number of resource types.<br/>
Third line, n numbers, each number indicates the number of units of the corresponding resource type.<br/>
Below followed by m lines, each line will consists of 2*n number. The first n numbers means the allocaton of n resources for the process, the second n numbers means the max_need of n resources.
(Note all numbers are separated by a single space)
</p>


For example:
<pre><code>
5
3
10 5 7
0 1 0 7 5 3
2 0 0 3 2 2
3 0 2 9 0 2
2 1 1 2 2 2
0 0 2 4 3 3
</code></pre>
Which means there are 5 processes, 3 resource types. The first resource type has 10 units, second one has 5 unites, third one has 7 units. The following line means the first process has a allocation of resource (0, 1, 0) and the max need is (7, 5, 3). Then following lines are the similar settings for process 2 unitl to process m.</br>
**You could [download the input file here](https://github.com/CS3502/Homework4/blob/master/input.txt)**


# Output:
The program should simply print out false on console if the system is not in safe state. Otherwise, print out true and one safe sequence consists of process number (numbers are separate by space).


# What to submit
<p>
Your implementation should contain a main method, which will by default read a file named as input.txt in the same directory (Suppose your jar file is in /home/xxx/hw4/jars/xx.jar, then the input.txt should be put in the same directory).
</br>
Export your program as a runnable jar.
</br>
Name your jar file as "netid".jar, e.g., My jar file will be gliu5.jar</br>
Test out your runnable jar file bying using command `java -jar netid.jar`</br>
And check the output.</br>
Rename your jar to "netid".jar and upload it under /home/gliu5/homework/hw4/
</p>


# Note
**When grading, the input.txt file used may be different from the above example.**
