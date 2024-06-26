# xv6 Lottery Scheduler and System Calls

## Overview
This project involved implementing a lottery scheduler, a user program `ps`, and several system calls in a Unix-like operating system.

## Project Details

### What I Accomplished:
- **Lottery Scheduler**: Implemented a scheduler that allocates CPU time based on the number of tickets each process holds.
- **System Calls**:
  - `setColor(enum COLOR)`: To set the color attribute of a process.
  - `setTickets(int)`: To set the number of tickets for a process.
  - `getpinfo(struct pstat *)`: To retrieve information about all running processes.
- **Pseudo Random Number Generator**: Integrated a simple pseudo-random number generator into the kernel.
- **ps Application**: Built a command-line program to display process information including name, PID, status, color, and tickets.
- **Process Inheritance**: Ensured child processes inherit the number of tickets from their parent process.
- **Testing and Validation**: Conducted thorough testing to ensure the correct functionality of the scheduler and system calls.
- **Report**: Created a graph showing the number of time slices received by three processes with a 3:2:1 ticket ratio, demonstrating the effectiveness of the lottery scheduler.

## Conclusion
This project deepened my understanding of process scheduling, system calls, and kernel development in a Unix.
