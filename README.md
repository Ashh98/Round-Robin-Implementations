# Round Robin Implementations

This project is an implementation of different versions of Round Robin algorithms for CPU scheduling.

## Description

Four different Round Robin algorithms are discussed. The first one is the classical Round Robin version, and then two different advanced improved versions of Round Robin are tackled. Finally, a crossover algorithm between the two advanced algorithms is introduced.

#### Classical Round Robin

Classical Round Robin starts with looping over the processes queue such that each process is
appointed only for the determined time quantum. The loop shall keep functioning until no process
require anymore processing time for it to get done.

#### Improved Round Robin [1] (Abdulrahim et. al)
Abdulrahim’s Round Robin loops over the processes queue and allocates resources for each
process. If a process is processed and the remaining burst time of a that process is less than or
equal half of the quantum time the process is processed again until its completely finished.

#### Improved Round Robin [2] (Mishra et. al)

Mishra’s Round Robin uses dynamic time quantum selection criteria to set the time quantum.
The time quantum is set to be equal to the burst time of the first process, and when this process is
finished the time quantum is set to the burst time of the next process and so on.

#### Improved Round Robin
This improved version of Round Robin algorithm mainly aims to deliver a cross over
between the 2nd and 3rd algorithms. This improved version adopts the dynamic time quantum
selection criteria applied in Mishra’s Round Robin, and it also considers reproces

## Built With

- C++
- OOP
- Data Structures and Algorithms

## References

[1] Abdulrazaq Abdulrahim, Saleh E Abdullahi, Junaidu B. Sahalu, “A New Improved Round Robin (NIRR) CPU Scheduling Algorithm” International Journal of Computer Applications (IJCA), Volume 90, No. 4, March 2014.

[2] Manish Kumar Mishra, Abdul Kadir Khan, “An Improved Round Robin CPU Scheduling Algorithm”, Journal of Global Research in Computer Science, Vol. 3, No. 6, June 2012.
