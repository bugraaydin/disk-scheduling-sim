# Disk Scheduling Simulation  
  
This piece of code simulates the behavior of the following disk scheduling algorithms:  
- **FCFS** (First Come First Served)
- **SSTF** (Shortest Seek Time First)
- **LOOK**
- **CLOOK**

For a given set of disk requests, total time, average waiting time and standard deviation of waiting time is outputted. (Rotational latency is disregarded.)

## Requirements
- GCC 4.5 or later (Supports C99)
- GNU make

## Usage

Build by: 
```bash 
$ make
```
Run on input:
```bash
$ ./ds <num_of_disk_requests> <input_filename>
```

### Input format  
The input should be given as rows of ```<request_arrival_time> <request_cylinder>``` pairs, each row separated by an EOL character. 

## Sample Run
### Input:  
![Sample Input](/img/input.png)
### Output:  
![Sample Output](/img/output.png)  
Ending lines at the output shows name of the algorithm, total time required for all requests to be handled, average waiting time, and standard deviation of waiting times.


