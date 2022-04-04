# CPU-Process-Scheduling-Algorithms
Compile as:
g++ main.cpp FCFS.cpp Process.cpp Random.cpp RR.cpp SJF.cpp SRT.cpp

Format:
       ./a.out num_processes seed lambda tail context_switch alpha RR_time_slice > output.txt
 e.g., ./a.out 16 2 0.01 256 4 0.75 64 > output.txt


Simulation events are in output.txt
Algorithm results are in simout.txt
