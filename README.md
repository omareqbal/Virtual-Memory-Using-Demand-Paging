# Virtual-Memory-Using-Demand-Paging

This is a simulation of a virtual memory management system using demand paging. There are four modules -
1) Master - creates other modules and initialized the data structures like Page Table and TLB
2) Scheduler - responsible for scheduling various processes using FCFS algorithm.
3) MMU - translates the page number to frame number and handles page-fault, and also manages the
page table
4) Process - generates the page numbers from page reference string
