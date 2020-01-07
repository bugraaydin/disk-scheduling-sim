# Disk Scheduling Simulation  
  
This piece of code simulates the behavior of following disk scheduling algorithms:  
- **FCFS** (First Come First Served)
- **SSTF** (Shortest Seek Time First)
- **LOOK**
- **CLOOK**

For a given set of disk requests, total time, average waiting time and standard deviation of waiting time is outputted. 

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
<p style="font-size: 16px; font-weight:800;" align="center"> Input  </p>  
<p align="center">  <img width="150" src="/img/input.png">  </p>  
<p style="font-size: 16px; font-weight:800;" align="center"> Output </p>  
<p align="center">  <img width="300" src="/img/output.png">  </p>  

Ending lines at the output shows name of the algorithm, total time required for all requests to be handled, average waiting time, and standard deviation of waiting times.

## Contributors  
Written together with [Buğra Aydın](https://github.com/bugraaydin/)

