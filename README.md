# gr
Final project of the Network Management course of the Computer Science Bachelor's Degree @ University of Pisa.

| <b>Language</b> | <b>Description</b> |
| --------------- | ------------------ | 
| Lua | A [sysdig](https://github.com/draios/sysdig)’s chisel (little script that analyzes and extracts useful informations from the sysdig event stream) capable of monitoring the processes currently executed on the machine. By executing the script it is possible to analyze at regular time intervals the execution time and the number of opened and closed sockets for one specified process (or for all the processes in execution). By monitoring the number and type of system calls executed we are able to measure the performance of an application, to check if the QoS requirements are satisfied (and if not why), and to analyze the amount of resources requested. | 
