# pubDeadlockPreemptionGraphSim
Written in Python and using libraries: NetworkX, matPlotLib, and time. Simulates an operating system resource/process allocation protocol.
Reads 'instrcution set' from multiple files to determine the amount of resources and processes available. Each line tells you what syscall a process is making to a resource. 
Creates a graph using NetworkX and updates after each line read. Detects and prevents conditions leading to deadlock.
Enacts a preemptive deadlock avoidance algorithm. Code available upon request
